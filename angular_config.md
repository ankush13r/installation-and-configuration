# Install Nodejs and Angular

#### Install nodeJs, if we already have nodeSs, we can skip it.
- Download node from the oficial web https://nodejs.org/es/
- From the directory of downloads execute following commands.
In this case we will install node 16.14.0 LTS
  ``` bash
  $ tar -xf 'node-v16.14.0-linux-x64.tar.xz'
  $ mv 'node-v16.14.0-linux-x64' '~/node16'
  ```

-  Now we have nodeJs installed in our home directory, but we need to set path of node16, to make it global.
-  First make copy of the file ~/.bashrc to have backup, in the case. After open the file ~/.bashrc and add the following lines at the end of the file.
  ``` bash
  #Modified PATH
  PATH=~/node16/bin:$PATH
  ```
    
- Verify that you have installed node correctly by running the following command.
  ``` bash
  $ node -v
  ```
  ``` bash
  Output:
  v16.14.0
  ```
#### Install Angular
