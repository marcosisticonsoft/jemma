jGAL Service
============

This bundles is a GAL wrapper. It wraps all the GAL functions into the OSGi environment.
```
-Declipse.ignoreApp=true 
-Dosgi.noShutdown=true

-Dequinox.ds.print=false
-Dequinox.ds.debug=false


-Dit.telecomitalia.zgd.disable-restlet-console=false
-Dit.telecomitalia.zgd.gateway-root=http://localhost:9000
-Dit.telecomitalia.zgd.local-address=localhost
-Dit.telecomitalia.zgd.bind-device=true
-Djgal.debug=false

-Dzgd.dongle.uri=COM13
-Dzgd.dongle.speed=115200
-Dzgd.dongle.type=freescale

-Dzgd.watchdog=10000
-Dzgd.log.debug=true

-Dosgi.instance.area=file:D:/Temp/data/

-Dobr.repository.url=http://192.168.1.184/obr/repository.zip
-Dit.telecomitalia.backend.uri=http://192.168.1.184:8081


-Dorg.osgi.service.http.port=8080
-Dorg.eclipse.equinox.http.jetty.http.port=8080
-Dorg.eclipse.equinox.http.jetty.https.enabled=false
-Dorg.eclipse.equinox.http.jetty.https.port=443

-Dit.telecomitalia.ah.hap.client.cachedAttributeIdFilter=ah.eh.esp.energySum
-Dit.telecomitalia.ah.hap.client.cacheFilesDir=D:/Temp/data
-Dit.telecomitalia.ah.hap.client.fastForwardFactor=1

-Dit.telecomitalia.m2m.device.configDir=D:/Temp/data
-Dit.telecomitalia.m2m.device.serverAddress=10.38.0.1
-Dit.telecomitalia.m2m.device.serverPort=8080
-Dit.telecomitalia.m2m.device.connectionRetryTimeout=60000

-Dorg.apache.commons.logging.Log=org.apache.commons.logging.impl.SimpleLog
-Dorg.apache.commons.logging.simplelog.defaultlog=debug
-Dorg.apache.commons.logging.simplelog.showlogname=true
-Dorg.apache.commons.logging.simplelog.showShortLogname=true
-Dorg.apache.commons.logging.simplelog.showdatetime=false
-Dorg.apache.commons.logging.simplelog.log.it.telecomitalia.internal.ah.m2m=INFO
-Dorg.apache.commons.logging.simplelog.log.org.apache.commons.httpclient=ERROR
-Dorg.apache.commons.logging.simplelog.log.httpclient.wire.header=ERROR
-Dorg.apache.commons.logging.simplelog.log.org.apache.http=ERROR
-Dorg.apache.commons.logging.simplelog.log.org.apache.http.wire=ERROR
```