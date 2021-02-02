setHook("rstudio.sessionInit", function(newSession) {
  if (newSession)
    rstudioapi::navigateToFile('<file name>', line = -1L, column = -1L)
}, action = "append")
