## libsvm

### 1. 台湾大学林智仁教授主页    
LIBSVM -- A Library for Support Vector Machines  
https://www.csie.ntu.edu.tw/~cjlin  
svm_tutorial  
https://www.csie.ntu.edu.tw/~piaip/svm/svm_tutorial.html  
sample  
https://www.csie.ntu.edu.tw/~cjlin/papers/guide/data/  
explained  
http://bytesizebio.net/2014/02/05/support-vector-machines-explained-well/  

### 2. libsvm动手实践
./svm-train test.1  
./svm-scale test.1  
./svm-scale -l -1 -u 1 -s test.1.model.range test.1 > test.1.model.scale  
./svm-scale -s test.1.model.range test.1 > test.1.model.scale  
./svm-predict test.1 test.1.model test.1.predict  

### 3.demo  
https://github.com/clysto/libsvm-demo  

### 4.svm.h api
svm_train  
svm_save_model  
svm_load_model  
svm_predict  
 
### 5. 串口模组
JY61资料下载  
下载地址:http://download.wit-motion.com/download/JY61/JY61.rar  
把上面链接粘贴到浏览器直接下载（推荐使用）  
百度网盘资料下载  
百度网盘链接：https://pan.baidu.com/s/1faXCw7hHhxHU7g4CVXy9aw  
验证码：3q0s  

