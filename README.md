Steps to setup:  
1. Create docker network
```bash
docker network create wp_vue
```

2. Create container via docker-compose
```bash
docker-compose up -d
```

3. Setup wordpress by visiting  
http://localhost:8080/wp-admin/install.php

4. Front end is available on http://localhost:3000

5. A list of wp rest API routes are available on http://localhost:8080/?rest_route=/




