= README =

python seash.py

angiebird@browsegood !>loadkey angiebird
angiebird@browsegood !>as angiebird

angiebird@browsegood !>browse
angiebird@browsegood !>on browsegood

angiebird@browsegood !>list

copy IP information to host_list.txt

Example:

  %1         204.8.155.226:2888:v8      Fresh                               
  %2        129.32.84.160:2888:v10      Fresh                               
  %3          132.170.3.32:1224:v8      Fresh                               
  %4        128.138.207.45:1224:v6      Fresh                               
  %5         206.12.16.155:1224:v4      Fresh                               
  %6        137.165.1.114:1224:v10      Fresh                               
  %7         208.94.63.194:2888:v6      Fresh                               
  %8        192.12.33.102:2888:v10      Fresh                               
  %9        132.239.17.226:1224:v6      Fresh       

python build_connectivity_map.py host_list.txt >connection.txt

angiebird@browsegood !> upload ../context.txt
angiebird@browsegood !> run ../routing.repy 63166

angiebird@browsegood !> show log


