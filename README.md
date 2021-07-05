# Researching-GetClosestVehicle  
should be the same with Researching-GetRandomVehicleInSphere    
but GetClosestVehicle is way more faster than GetRandomVehicleInSphere    
want to get all car , bike and bicycle: not supported player is in  
entity = GetClosestVehicle( x,y,z, radius , 0 , 7 )  
want to get all car , bike and bicycle: supported player is in    
entity = GetClosestVehicle( x,y,z, radius , 0 , 23 or 127 or 2175 or 67711)  
  
want to get all car , bike and bicycle without polices: not supported player is in  
entity = GetClosestVehicle( x,y,z, radius , 0 , 2 )   
want to get all car , bike and bicycle without polices: supported player is in  
entity = GetClosestVehicle( x,y,z, radius , 0 , 94 )  
  
want to get all planes : not supported player is in  
entity = GetClosestVehicle( x,y,z, radius , 0 , 16390 )  
  
want to get all planes , helis: supported player is in  
entity = GetClosestVehicle( x,y,z, radius , 0 , 20503 )  
