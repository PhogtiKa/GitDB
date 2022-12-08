## Deploy on 
1. Install packages

```bash
npm install
```

2. Create file config .env.local in root folder

```
# key use to login
AUTH_USER = sfjsldkwioeurWER34dfgdf

# postgresql config 
PG_HOST = 127.0.0.1                 
PG_PORT = 5432                      
PG_USERNAME = osmuser
PG_PASSWORD = 123456
PG_DATABASE = osm
PG_SCHEMA = osm

# geoserver config
GEOSERVER_USER = admin
GEOSERVER_PASS = geoserver
GEOSERVER_URL = http://localhost:8080/geoserver
GEOSERVER_WORKSPACE = meey_map

# tool server config
NEXT_PUBLIC_BASE_PATH = /geoserver
NEXT_PUBLIC_MAX_UPLOAD_FILES = 10
NEXT_PUBLIC_MAX_FILE_SIZE = 209715200 # 200 MB
```

3. Build tool

```bash
npm run build
```

4. Run server tool (should start in screen)

```bash
npm start
```
