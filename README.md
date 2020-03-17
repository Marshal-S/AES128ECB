# AES128ECB

Byte key[] = {1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16} //key

Byte signal[] = {1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16}; //input

Byte encryptSignal[16]; //保存加密结果

Byte decryptSignal[16]; //保存解密结果

AES128_ECB_encrypt(signal, aeskey, encryptSignal);//AES 128加密

AES128_ECB_decrypt(signalByte, aeskey, decryptSignal);//AES 128解密

