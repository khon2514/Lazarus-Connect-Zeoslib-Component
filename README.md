# Lazarus-Connect-Zeoslib-Component
สำหรับเชื่อมต่อ zeoslib component
การเรียกใช้งาน connect mysql

  if not FileExists(Z4ini1.Filename) then
   begin
     Z4ini1.SetConnection;
     Application.Terminate;
     exit;
   end;
  try
   Z4ini1.Execute;
  except
    Z4ini1.SetConnection;
  end;  
![image](https://user-images.githubusercontent.com/44339462/113791543-176abd00-976e-11eb-8129-fc28f6f18944.png)
