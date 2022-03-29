1. mongo 5.x不支持x86_x64  
   MongoDB 5.0+ requires a CPU with AVX support, and your current system does not appear to have that!   
  see https://jira.mongodb.org/browse/SERVER-54407  
  see also https://www.mongodb.com/community/forums/t/mongodb-5-0-cpu-intel-g4650-compatibility/116610/2  
  see also https://github.com/docker-library/mongo/issues/485#issuecomment-891991814