# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS 
    "ApiStore.cpp" 
    "AWSIntegration.cpp" 
    "Config.cpp" 
    "CriticalSection.cpp" 
    "DisplayCharter.cpp" 
    "DisplayCharterLogo.cpp" 
    "DotstarStripe.cpp"
    "DynamicRequestHandler.cpp"
    "DynatraceAction.cpp"
    "DynatraceIntegration.cpp"
    "DynatraceMonitoring.cpp"
    "HttpRequestParser.cpp"
    "HttpResponse.cpp"
    "HttpResponseParser.cpp"
    "Ota.cpp"
    "StateDisplay.cpp"
    "stdlib_noniso.c"
    "String.cpp"
    "StringParser.cpp"
    "Ufo.cpp"
    "UfoWebServer.cpp"
    "Url.cpp"
    "UrlParser.cpp"
    "WebClient.cpp"
    "WebServer.cpp"
    "Wifi.cpp"
    )
set(COMPONENT_ADD_INCLUDEDIRS "" ".")

# set(COMPONENT_EMBED_FILES index.html favicon.ico timepicker.less less.min.js)

set(COMPONENT_EMBED_TXTFILES certkey.pem)

register_component()