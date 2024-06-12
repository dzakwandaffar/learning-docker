# Projek My Docker Compose

1. Prepare single database, single table, and single column, for timestamp
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/3f1e5f0f-d1df-4f45-a697-f2abfc429ecb)
   
3. Create golang project, and add route "/ping" if can connect to database, output to browser is Pong! and console is Ping Successful, if failed, Ouch and console is Ping Failed. And can show timestamp if connected.
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/cb0dee6b-2dd8-46fd-9ab8-9c9bc37a7158)

   
5. Created docker-compose.yml for run 2 container, set container name, network name, also volume name
  ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/636646c0-9410-4421-bcbe-c757d85af644)

   
7. Create docker compose and can see on docker desktop
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/5d7bccd6-562e-48dd-89c8-4b5197ed8890)

   
9. Run localhost:4331 and show word that have been created
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/4c19ca46-54f1-44e4-8bf8-9ec073a7467e)

    
11. Run localhost:4331/ping and show pong for success and new data timestamp inserted in database
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/23ef9778-1d59-45cb-aa3b-4c0a0bc1455a)
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/0668b618-aea8-427c-bc81-0a3a517f2fa8)

    
13. Check log from each container
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/e348b8cf-beb0-45e4-a194-72d880ee3132)
    ![image](https://github.com/dzakwandaffar/learning-docker/assets/99236283/8bdc7011-729f-4cfe-844c-89bcd44b73ea)

