
# Crypto 

## Mix

At the `BASE`ment no. `65536`,
A man is irritated with 
`SHIFT` key in his `KEYBOARD` 
as it's a sticky key, 
A kid is having chocolate 
icecream with a `SPOON`.

Author : Whit3_D3vi1

File : [Mix.zip](Assets//Files/Mix.zip)

**Solution:**

> Fast of all , the challenge description has everything you need to find out the flag.

At first when I unzip the `Mix.zip` archived file I got two new file under the Mix folder

1. [flag.txt](Assets//Files/Mix/flag.txt)

file data: 

```
	If you opened this then you are a n00b 
```


2. [chall_encrypted.txt](Assets//Files/Mix/chall_encrypted.txt)

file data :

```
ꍦ鱡映㸺ꅙ饯𒀠啤啳𓁬𐙵𓅰魴餠𒁪𖥧𔐠遯𓁪𖥴顲啹𓁪𓁴𒀠啤𒅵啩灧鵳𖠠楪扴詽鸭餫𓉩怴㸊ꍦ鱡朠㸺攳攳昳昳攳昳攳攳攲攳昳昳昳攳攳昳攳攲攳攳昳昳攳攳昳昳攲攳昳攳昳昳昳昳昳攲攳攳昳昳攳昳攳攳攲攳昳昳昳攳昳昳昳攲攳攳昳昳攳攳昳昳攲攳昳昳昳攳攳昳昳攲攳攳昳昳攳攳攳攳攲攳昳昳攳昳昳攳昳攲攳攳昳昳攳攳昳昳攲攳昳攳昳昳昳昳昳攲攳昳昳昳攳昳昳昳攲攳昳昳攳昳攳攳昳攲攳攳昳昳攳昳昳昳攲攳昳昳攳昳攳攳攳㸊ꍦ鱡栠㸺襍𖡅襍𖡅襍𖡅襍𔕁襍𔕁祍𔕅襍𖡁祍𖡅襍𖡁祍𖡅襍𖡅襍𔕅襍𖡁襍𖡅襍𖡅襍𖡅祍𖡅祍𖡅祍𖡅祍𖡅祍𔕁祍𖡁襍𖡁祍𖡁祍𖡁祍𖡁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁襍𖡁祍𖡁襍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁襍𖡁祍𔕁祍𔕁祍𔕁祍𔕁襍𖡁祍𔕁襍𖡁祍𖡁祍𔕁襍𖡁祍𖡁襍𖡅襍𖡅襍𔕁襍𖡁祍𖡁祍𖡅襍𖡅襍𖡅襍𔕁襍𖡁祍𖡁襍𔕁祍𔕁祍𔕁祍𔕁祍𔕁襍𖡁祍𖡁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁襍𖡁祍𖡅襍𖡅襍𖡅襍𖡅襍𖡅襍𖡅襍𖡅祍𖡁祍𔕅祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𔕁祍𖡁祍𔕅祍𔕁祍𔕁祍𖡁祍𔕅祍𖡅祍𔕁祍𔕁祍𖡁祍𔕅祍𖡁祍𔕅襍𖡅襍𔕁襍𖡁祍𖡁祍𖡅襍𖡅襍𖡅襍𖡅襍𖡅襍𖡅襍𖡅祍𖡁祍𔕅祍𖡅祍𖡅祍𖡅襍𖡅襍𖡅襍𖡅襍𔕁襍𖡁癍爽ᔊ
```

The `flag.txt` file contents are not so interesting so we have move forward to the `chall_encrypted.txt` file.
At first, when I saw the the content of the file I thought that I have to translate that shitty thing.
For this I goes to [google translate](https://translate.google.co.in/) but it couldn't find anything (except some gibberish).
After this I returned back to the main site & read the challenge description properly.
At this time I saw there are some words which are highlited into bold.
After seeing the first highlited word I have got a question in my mind that is the cipher text is any type of base encrypted data.
To find out the answer I just searched on google for the first two highlited words together & I found that the encrypted data is 
a [base65536](https://www.better-converter.com/Encoders-Decoders/Base65536-Decode) hash encrypted text.
After decoding that file data I got this :

```

flag 1:
Yjod od s lrunpstf djogy vo[jrtyrcy jrtr od upi g;sh xj4t-}U-i+dit4+

flag 2:
3030313130313030203031313130303130203030313130303131203031303131313131203030313130313030203031313130313131203030313130303131203031313130303131203030313130303030203031313031313031203030313130303131203031303131313131203031313130313131203031313031303031203030313130313131203031313031303030

flag 3:
MTExMTExMTExMTAwMTAwMDEwMTAxMDExMTAxMDExMTExMTEwMTAxMTExMTExMTExMDExMDExMDExMDExMDAwMDAxMTAxMDAxMDAxMDAxMDAwMDAwMDAwMDAwMDAwMDAwMTAxMDAxMTAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMTAxMDAwMDAwMDAwMDAwMTAxMDAwMTAxMDAxMDAwMTAxMDAxMTExMTExMTAwMTAxMDAxMDExMTExMTExMTAwMTAxMDAxMTAwMDAwMDAwMDAwMDAwMTAxMDAxMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMTAxMDExMTExMTExMTExMTExMTExMTExMDAxMDEwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAxMDEwMDAwMDAwMDAxMDEwMDExMDAwMDAwMDAxMDEwMDAxMDEwMTExMTAwMTAxMDAxMDExMTExMTExMTExMTExMTExMTExMDAxMDEwMDExMDExMDExMTExMTExMTExMTAwMTAxMA==

```

These are the main three parts of the flag.
The first one is [Shift Keyboard](https://www.dcode.fr/keyboard-shift-cipher) encrypted data as the next highlited word from the challenge description says.
After decoding this I got the first part of the flag.

```
zh3r0{Y0u_sur3_

```

The middle one is looks like some decimal number presentation of the middle part of the flag.
But I am wrong. When I was googling for this I got [this artical](https://www.reddit.com/r/codes/comments/evz1uk/riddle_from_discord_coding_language_if_you_could/) that have this following text.

```
Hex ascii codes. 20 = Space, 30 = 0, 31 = 1.

```

There after, first I have turned the [hex into ascii](https://www.rapidtables.com/convert/number/hex-to-ascii.html) format & I got some binaries. After that I turned the [binary to text](https://www.rapidtables.com/convert/number/binary-to-ascii.html) format.
And yup I got the middle part of the flag.

```
4r3_4w3s0m3_wi7h

```

The third one is [base64](https://www.base64decode.net/) encoded data. After decoding this I got another cipher text which looks like some 
binary data but that is a [Spoon](https://www.dcode.fr/spoon-language) cipher as the last highlited word from the challenge description says
& yeah I got the last part of the flag as well.

```
_411_7h3_ski115}

```

**flag:**```zh3r0{Y0u_sur3_4r3_4w3s0m3_wi7h_411_7h3_ski115}```

