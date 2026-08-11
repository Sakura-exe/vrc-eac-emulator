message(STATUS "Fetching crashlog...")

FetchContent_Declare(
  crashlog
  GIT_REPOSITORY https://github.com/huzun1/crashlog
  GIT_TAG        90d3a45edefe2320643499a48574ce973d3e6354
)

FetchContent_MakeAvailable(crashlog)
