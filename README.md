# essay-test

1. ```php 
    $v = '1,2,3,4,5,6,7';
    $sum = array_sum(explode(',', $v));
    echo $sum;
    ```
1. a. Email
   ```php
   $email = "test@gmail.com";
   if (filter_var($email, FILTER_VALIDATE_EMAIL)) {
       echo "valid email address";
   } else {
      echo "not a valid email address";
   }
   ```
   
   b. Phone
   ```php
   $phone = '123';
   if (is_numeric($phone)) {
      echo "valid phone number";
   } else {
      echo "not a valid phone number";
   }
   ```
   
   c. Name
   ```php
   $name = 'example';

   if(preg_match("/^([a-zA-Z' ]+)$/",$name)){
      echo 'Valid name.';
   }else{
      echo 'Invalid name.';
   }
   ```
  1.
  1.
  1. cara cepat -> `ob_start();`
  1. `7`
  1. - Model -> Bertugas untuk mengatur, menyiapkan, memanipulasi dan mengorganisasikan data (dari database) sesuai dengan     instruksi dari controller.
     - View -> Bertugas untuk menyajikan informasi (yang mudah dimengerti) kepada user sesuai dengan instruksi dari controller.
     - Controller -> Bertugas untuk mengatur apa yang harus dilakukan model, dan view mana yang harus ditampilkan berdasarkan permintaan dari user. Namun, terkadang permintaan dari user tidak selalu memerlukan aksi dari model. Misalnya seperti menampilkan halaman form untuk registrasi user.
  1. Next latter is T
  1.
  1.
