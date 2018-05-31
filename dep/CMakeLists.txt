if (CTI_CONTINUABLE_WITH_TESTS OR CTI_CONTINUABLE_WITH_EXAMPLES)

  if(NOT TARGET asio)
    add_subdirectory(asio)
  endif()
endif()
