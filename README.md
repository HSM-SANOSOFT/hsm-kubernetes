# HS-KUBERNETES

## General Commands

### Docker Cleanup
1. `docker-compose down`
2. `docker system prune`
3. `docker volumes prune`
4. `docker image prune`
5. `docker network prune`
6. `docker container prune`
7. `docker builder prune`

### Docker Compose
1. `docker-compose --env-file ./envs/global.env up --build`
2. `docker-compose --env-file ./envs/global.env build`
3. `docker-compose --env-file ./envs/global.env up -d`
4. `docker-compose --env-file ./envs/global.env up -d --no-build`

---

## Microservices

### Gateway Service
1. View logs: 
   - `docker-compose logs -f HSM-BE-GATEWAY-MS`
2. Build: 
   -`docker-compose --env-file ./envs/global.env build HSM-BE-GATEWAY-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-GATEWAY-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-GATEWAY-MS --no-build`
5. Server 
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-GATEWAY-MS`

### Auth Service
1. View logs:
   - `docker-compose logs -f HSM-BE-AUTH-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-AUTH-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-AUTH-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-AUTH-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-AUTH-MS`
  
### Coms Service
1. View logs:
   - `docker-compose logs -f HSM-BE-COMS-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-COMS-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-COMS-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-COMS-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-COMS-MS`
  
### Common Service
1. View logs:
   - `docker-compose logs -f HSM-BE-COMMON-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-COMMON-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-COMMON-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-COMMON-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-COMMON-MS`
  
### Examenes Service
1. View logs:
   - `docker-compose logs -f HSM-BE-EXAMENES-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-EXAMENES-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-EXAMENES-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-EXAMENES-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-EXAMENES-MS`
  
### Facturacion Service
1. View logs:
   - `docker-compose logs -f HSM-BE-FACTURACION-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-FACTURACION-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-FACTURACION-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-FACTURACION-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-FACTURACION-MS`
  
### Farmacia Service
1. View logs:
   - `docker-compose logs -f HSM-BE-FARMACIA-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-FARMACIA-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-FARMACIA-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-FARMACIA-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-FARMACIA-MS`
  
### Hospitalizacion Service
1. View logs:
   - `docker-compose logs -f HSM-BE-HOSPITALIZACION-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-HOSPITALIZACION-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-HOSPITALIZACION-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-HOSPITALIZACION-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-HOSPITALIZACION-MS`
  
### Medicos Service
1. View logs:
   - `docker-compose logs -f HSM-BE-MEDICOS-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-MEDICOS-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-MEDICOS-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-MEDICOS-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-MEDICOS-MS`
  
### Pacientes Service
1. View logs:
   - `docker-compose logs -f HSM-BE-PACIENTES-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-PACIENTES-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-PACIENTES-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-PACIENTES-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-PACIENTES-MS`
  
### Personal Service
1. View logs:
   - `docker-compose logs -f HSM-BE-PERSONAL-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-PERSONAL-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-PERSONAL-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-PERSONAL-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-PERSONAL-MS`
  
### Users Service
1. View logs:
   - `docker-compose logs -f HSM-BE-USERS-MS`
2. Build:
   - `docker-compose --env-file ./envs/global.env build HSM-BE-USERS-MS`
3. Start (build included):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-USERS-MS`
4. Start (no build):
   - `docker-compose --env-file ./envs/global.env up -d HSM-BE-USERS-MS --no-build`
5. Server
   - `docker-compose -f docker-compose.prod.yml --env-file ./envs/global.env up -d --no-deps HSM-BE-USERS-MS`
  