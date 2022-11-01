import socket

def ip_scanner():
  
     target_name = input("Enter The Target Name = ")
     
     try:
         ip_address=socket.gethostbyname(target_name)
         
         print("Target name: %s" %(target_name))
         print("Ip address of the target : %s" %(ip_address))
         
     except socket.error as err_msg:
         print("%s %s" %(target_name,err_msg))
         
if __name__=='__main__':
  ip_scanner()
