# Lazarus-Connect-Zeoslib-Component
สำหรับเชื่อมต่อ zeoslib component
การเรียกใช้งาน

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
