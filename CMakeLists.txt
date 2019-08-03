set(COMPONENT_SRCS main.c MyWiFi.c OTAServer.c)
set(COMPONENT_ADD_INCLUDEDIRS "")

set(COMPONENT_EMBED_TXTFILES WebsiteFiles/index.html WebsiteFiles/favicon.ico WebsiteFiles/jquery-3.3.1.min.js)

register_component()