web: java -Dmockserver.enableCORSForAllResponses=true \
          -Dmockserver.corsAllowMethods="CONNECT, DELETE, GET, HEAD, OPTIONS, POST, PUT, PATCH, TRACE" \
          -Dmockserver.corsAllowHeaders="Allow, Content-Encoding, Content-Length, Content-Type, ETag, Expires, Last-Modified, Location, Server, Vary, Authorization" \
          -Dmockserver.corsAllowCredentials="true" \
          -Dmockserver.corsMaxAgeInSeconds="300" \
          -Dmockserver.corsAllowOrigin="*" \
          -jar mockserver-netty-5.13.2-shaded.jar -serverPort ${PORT:-3000}