# postman_collection
postman_collection_and_all_config_files
Jenkins command to run this collection
newman run KIBO_Quartz_Server.postman_collection -d data.json -g globals.json -e env.json --reporters=cli,htmlextra --disable-unicode
