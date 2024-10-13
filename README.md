# khazad
Khazad block cipher cryptosystem implementation in python3 and test vectors (pure implementation for learning not using LUTs)

Non linear layer
1. 0xbbada7ace1bcdd97 -> 0xca4f0005d59f16c4
2. 0xb225fbf891794bfb -> 0xafa813a40a072813
3. 0xf6ce55dd6ac237eb -> 0xc76f5216d19cffcd

Linear layer
1. 0xbbada7ace1bcdd97 -> 0x3a43f585e0a05516
2. 0xb225fbf891794bfb -> 0xe399a1caec1cdff2
3. 0xf6ce55dd6ac237eb -> 0x16e905dff90bbead

Key schedule
Key = 0x40000000000000000000000000000000

0. 0x407441d6770beade
1. 0xa015125c5fadd7a
2. 0x1e4a92017867295d
3. 0x7b317ad5a2dc53ec
4. 0xeb068955b69951dc
5. 0xbedfa65293a1439f
6. 0xe21d3111ca820ba2
7. 0xb733fd455dc42287
8. 0x47ed51ccff5248ff

key = 0x80000000000000000000000000000000

0. 0x807441d6770beade
1. 0xadf5f72430ab7828
2. 0x324629ba140c3982
3. 0xe7416d14a8bd26bd
4. 0x3df17e33e28b5c61
5. 0x79f39fc4d0fa11d1
6. 0x3d1b8ac1733f0414
7. 0xb91b034456a5bf2e
8. 0x3377494c15c7b14b

Encrypt process with
Key = 0x80000000000000000000000000000000

plaintext = 0x0

1. 0x3ac991fc1e4754bd
2. 0x215438aa031a2c96
3. 0xc6ba4f47f8ea220d
4. 0x5313cf56f6eab413
5. 0xaaacb4003fcd12f
6. 0xa4df23c4b20a110c
7. 0x4c023b268faa1afa
8. 0x1491c287b5ed74de

Cipher text: 0x1491c287b5ed74de

Decrypt process with
Key = 0x80000000000000000000000000000000

Cipher text: 0x1491c287b5ed74de

1. 0xf821da97af91a51e
2. 0x912a267c710b6af9
3. 0x48fb81eac756a3fb
4. 0x65eead0da4562947
5. 0xdf0e602a71c54176
6. 0x8090a0b0c0d0e0f
7. 0xdbb92c876bfc5666
8. 0x0

Plain text: 0x0


Encrypt process with
Key = 0x40000000000000000000000000000000

Plain Text = 0x0

1. 0x3ac991fc1e4754bd
2. 0xd5883116f713c49
3. 0xa8101ad6a4e93857
4. 0x706bd68ac61613d7
5. 0x5b3ed28ad274fd17
6. 0x31be23dbd82c2540
7. 0x13073edefc1cf35c
8. 0xbc942eaaf4fbb5ae

Cipher text: 0xbc942eaaf4fbb5ae

Decrypt process with
Key = 0x40000000000000000000000000000000

Cipher text: 0xbc942eaaf4fbb5ae

1. 0xe21bda808d41a87c
2. 0x587f436143b9f3d4
3. 0x2d77876165ddfbf5
4. 0x258cc587f8f16042
5. 0x475bcca5ce035e94
6. 0x8090a0b0c0d0e0f
7. 0x7cb92c876bfc5666
8. 0x0

Plain text: 0x0
