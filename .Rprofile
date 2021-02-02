setHook("rstudio.sessionInit", function(newSession) {
    if (newSession)
        rstudioapi::navigateToFile('preregRS.Rmd', line = -1L, column = -1L)
}, action = "append")
