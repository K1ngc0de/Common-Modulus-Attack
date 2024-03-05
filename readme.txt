Algorithm

1. Step 1st.

    analyze the file with pub KEY with linux command: 
        openssl rsa -pubin -in pubkey_1.cer -text -noout

        FOR EXAMPLE.
    pubkey_1.cer
        Public-Key: (255 bit)
        Modulus:
            65:af:e6:d7:bf:2b:d8:6c:2b:57:ad:6d:67:47:ea:
            1e:4f:37:df:44:a4:0b:c0:0e:10:61:71:7f:6b:97:
            e5:1f
        Exponent: 5501 (0x157d)

    
    pubkey_1.cer
        Public-Key: (255 bit)
        Modulus:
            65:af:e6:d7:bf:2b:d8:6c:2b:57:ad:6d:67:47:ea:
            1e:4f:37:df:44:a4:0b:c0:0e:10:61:71:7f:6b:97:
            e5:1f
        Exponent: 6529 (0x1981)

    !!! Promise that Modulus equal in both public key.

2. Step 2nd.

    Conversion modulus from 16-currency to 10-currency and use dec.py.

3. Step 3rd.

    Conversion plaintext from 10-currency to 16-currency, than from 16-currency to text.


FLAG: n3v3r_u53_th3_54m3_m0dulu5


