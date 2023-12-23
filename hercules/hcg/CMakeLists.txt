zephyr_library()

set(TI_HERCULES_SOC_LIST
    rm46l852
    tms570lc43xx
)

foreach(HERCULES_SOC ${TI_HERCULES_SOC_LIST})

  string(TOUPPER ${HERCULES_SOC} HERCULES_SOC_TO_UPPER)

  if(CONFIG_SOC_SERIES_${HERCULES_SOC_TO_UPPER})

    add_subdirectory(${HERCULES_SOC})
    
  endif()

endforeach()