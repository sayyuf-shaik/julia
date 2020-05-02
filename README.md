# julia
julia examples
# Julia installation
Getting latest julia from julia's official website
- wget https://julialang-s3.julialang.org/bin/linux/x64/1.0/julia-1.0.5-linux-x86_64.tar.gz
Untar the downloaded tar file
- tar -xvf julia-1.0.5-linux-x86_64.tar.gz
After Extracting goto the julia folder
- cd julia-1.0.5/
Copy the julia's folder to the /opt
- sudo cp -r julia-1.0.5 /opt/
Create a symbolic link for the julia
- sudo ln -s /opt/julia-1.0.5/bin/julia /usr/local/bin/julia
Type julia to test. You would be able to see like this.
sayyuf@sayyuf:~$ julia
               _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.0.5 (2019-09-09)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

julia> 2 + 3
5

julia> ans
5




