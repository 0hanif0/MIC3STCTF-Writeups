# MIC3STCTF Writeups
- Link: [https://ctf.mic3st.com/](https://ctf.mic3st.com/)
- In these writeups, I use the Malay language.

## level 1 > level 2

![image](https://user-images.githubusercontent.com/23289982/205048057-8ec0a9bf-ef21-4b63-b610-c358a88ce32b.png)
 
 * right click dan tekan `view page source`
 
 ![1](https://user-images.githubusercontent.com/23289982/205049089-d529fe54-3287-4a6e-9e11-56b3618e2ff3.png)
 
 * tekan `2.html` untuk ke level 2
 
 ## level 2 > level 3
 
 ![image](https://user-images.githubusercontent.com/23289982/205049392-f6f3b120-9338-4974-a548-56088dd122c2.png)

 ![2](https://user-images.githubusercontent.com/23289982/205050088-7e65ebef-b390-4b94-996f-ec368cab2898.png)

* tukar kt URL menjadi `3.html` akan masuk page seterusnya tetapi belum habis disitu

![3](https://user-images.githubusercontent.com/23289982/205051271-f1927cb0-0fa7-41a0-9c6c-ca04fad6f927.png)

* copy flag tersebut dan letak di bahagian submit dan tekan submit untuk ke level 3

## level 3 > level 4

![image](https://user-images.githubusercontent.com/23289982/205052225-90b24445-1f5d-4c2f-890f-f5bdca38e7c3.png)

* macam biasa buka `view page source` untuk cari hint

![4](https://user-images.githubusercontent.com/23289982/205052498-d2d32082-5d8f-41bb-914d-710929355d52.png)

![5](https://user-images.githubusercontent.com/23289982/205053069-711aa0ed-9f9b-467b-bc29-db2fa60bdb48.png)

* berdasarkan hint tersebut kita lihat bahawa untuk level 3 ini dia menggunakan huruf roman
* dan perlu `replace flag with number four`

![6](https://user-images.githubusercontent.com/23289982/205053962-60fd314a-325d-4973-9c2d-7671d25f6655.png)

* dan enter untuk ke page seterusnya

![7](https://user-images.githubusercontent.com/23289982/205054583-7123c36e-ae25-4cd7-ac40-a79f9a608349.png)

* seterusnya right click dekat link dan tekan `open link in new tab` akan bawa ke page seterusnya

![8](https://user-images.githubusercontent.com/23289982/205055145-0da4d00e-5c25-4f5b-9d5a-6fe5f76a3d85.png)

* dapat banyak nama terpapar kan
* hint tersebut sebenarnya ialah nama untuk robot2 yang ada dalam movie
* dan ia merujuk kepada [robots.txt](https://developers.google.com/search/docs/crawling-indexing/robots/intro#:~:text=What%20is%20a%20robots.txt%20file%20used%20for%3F,-A%20robots.txt&text=You%20can%20use%20a%20robots,similar%20pages%20on%20your%20site.) nak tahu sebab dia boleh tekan link

![9](https://user-images.githubusercontent.com/23289982/205056632-a1a4f658-2c95-4bb8-9522-ca6bfdbbda20.png)

* korang letak je `robots.txt` macam dalam gambar dan tekan enter untuk page seterusnya

![10](https://user-images.githubusercontent.com/23289982/205057505-3e5812ef-c5bc-4a2b-8955-839baf2c00b1.png)

* korang tengok dekat allow tu korang replace balik URL sebelum `robots.txt` kepada `robots/txt` akan ke page seterusnya

![11](https://user-images.githubusercontent.com/23289982/205058315-b668dc40-4d8f-4bec-aca3-0e2a8ffcb1f1.png)

* korang tekan je QR tu dan decode gambar QR 
* guna lah kreativiti korang nak scan QR tu 
* nanti akan dapat flag untuk di submit
* lepastu korang submit dekat page yang kena submit tu untuk ke level 4

## level 4 > level 5

![12](https://user-images.githubusercontent.com/23289982/205059617-6097ccb5-7d79-462e-b7c5-38259b06830b.png)

![13](https://user-images.githubusercontent.com/23289982/205059887-4a5b15a5-8cb4-4766-b4b6-a7844e2601dc.png)

* korang tambah je o tu kt URL jadi `ooooo` akan ada hint dekat page seterusnya

![14](https://user-images.githubusercontent.com/23289982/205060576-0dd46073-7468-4c76-b2b1-0e509c9b8917.png)

* hint seterusnya ialah `eat something`
* bagi aku hint ni maksudnya cookies sebab dekat website biasa ada cookies
* seterusnya korang edit cookies

![15](https://user-images.githubusercontent.com/23289982/205062789-87a1bba7-91ce-4540-aa35-4932cecd59b8.png)

* nak edit cookies korang right click tekan `inspect element`
* macam dalam gambar korang tekan `application` > `cookies` > dan korang edit value kepada `true`

![image](https://user-images.githubusercontent.com/23289982/205063399-3cf81c89-b1cc-4453-8be0-3ef58dde0229.png)

* lepas edit kepada `true` korang refresh balik page
* korang akan dapat QR 2 yang perlu di decode
* untuk QR 2 ni dia ada beza sedikit dengan QR 1 jika di compare
* korang download je dulu QR 2 tu
* QR 2 ni perlu di edit sebab scanner tak dapat detect
* pertama sekali korang kena edit color QR sebab color dia sebenarnya invert 
* korang boleh guna tools online ni [INVERT COLORS ONLINE](https://pinetools.com/invert-image-colors) untuk edit color

![image](https://user-images.githubusercontent.com/23289982/205069818-67515a68-a676-4774-9445-b117c3ed3905.png)

* korang download je dulu gambar yang sudah invert
* seterusnya korang kena edit dekat bahagian petak QR
* kena tambah sedikit petak kena edit QR

 ![16](https://user-images.githubusercontent.com/23289982/205071053-58e527ac-6abd-4f3b-a005-93c41dde7d20.png)

* edit macam dalam gambar, guna kreativiti korang macam mana kalau aku pakai paint je
* lepastu korang scan QR akan dapat link untuk flag

![17](https://user-images.githubusercontent.com/23289982/205072196-081c0461-7baa-4590-ac63-120fef1c6405.png)

* macam biasa korang `view page source` untuk cari hint

![18](https://user-images.githubusercontent.com/23289982/205072304-12fc7f30-e8c4-465d-b508-f7ef11faa658.png)

![19](https://user-images.githubusercontent.com/23289982/205072907-44819575-21b7-46a0-a2dd-954e2b11671f.png)

* korang replace je URL macam dalam gambar untuk page seterusnya

![20](https://user-images.githubusercontent.com/23289982/205073051-f7c10b24-321d-4c73-8ce3-d392f694e14e.png)

 * korang submit je flag yang dapat dari QR 2 ke sini 
 * dan korang berjaya untuk ke level 5

## level 5 > level 6

![image](https://user-images.githubusercontent.com/23289982/205073605-a2d03981-3b1a-4a4b-b624-9e3bc84c2a92.png)

![21](https://user-images.githubusercontent.com/23289982/205302809-f84060a5-5675-434b-86ea-b06bd39a2475.png)

* korang replace URL mcm dlm gambar untuk hint seterusnya

![22](https://user-images.githubusercontent.com/23289982/205303099-0354e035-68b5-4841-bddc-5b236b8f64d4.png)

* hint `<trut tut tut tut tut></trut>` bermaksud ini adalah morse code

* korang translate no 6 guna [morse code translator](https://morsecode.world/international/translator.html) akan dapat output
* kenapa no 6 sebab kita nak ke level 6
* korang replace je morse code tersebut macam gambar bawah

![23](https://user-images.githubusercontent.com/23289982/205304180-d53ce2fb-4024-4854-b9d6-0e0f272b5496.png)

* korang akan ke page seterusnya ialah finale

![image](https://user-images.githubusercontent.com/23289982/205304427-e4e5b515-61ae-4c4d-9b1b-ecad416e78ea.png)

* dekat finale korang tekan `terminal` in new tab dan `view page source`
* masa dekat `terminal` tu korang kena cepat cepat buka `view page source` sebab ada timer untuk redirect ke page lain

![24](https://user-images.githubusercontent.com/23289982/205305091-c2ab87e9-565f-46a8-a81e-1e80d1f5d940.png)

![27](https://user-images.githubusercontent.com/23289982/205306018-bbe9c72d-2657-4fe7-97d6-6899a853c63b.png)

* itu adalah hint pertama untuk gambar dibawah

![image](https://user-images.githubusercontent.com/23289982/205306242-8e60d804-eb00-48db-be4b-bd3f3c57df30.png)

* selepas dah buka korang tekan `./script.js` untuk hint seterusnya

![25](https://user-images.githubusercontent.com/23289982/205305752-a42d3d57-a5eb-4d5c-957a-ed81a98af2d5.png)

![26](https://user-images.githubusercontent.com/23289982/205305765-0a835a39-8c4f-4d0f-b5f8-25d37c8d3d0d.png)

* di page ini terdapat dua hint iaitu `md5 $agent.code` dan `MD5 ALL CAPS`
* berdasarkan hint tersebut kemungkinan page ini menggunakan [user agent](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/User-Agent) nak tahu kenapa user agent korang boleh tekan link tersebut
* untuk hint tersebut bermaksud korang perlu menggunakan hash md5
* korang boleh pakai tools [MD5 Hash Generator](https://www.md5hashgenerator.com/)

![image](https://user-images.githubusercontent.com/23289982/205307757-1c64e089-2761-4c82-a30a-65d9af426b37.png)

* korang hash sahaja `007`
* kenapa 007 sebab hint kat atas tadi ada sebut `bond`
* bond dan 007 korang boleh tahu di dalam movie james bond
* seterusnya hint ke kedua ialah semua hash tersebut perlu di UPPERCASE
* korang akan dapat `9E94B15ED312FA42232FD87A55DB0D39` untuk digunakan dalam user agent
* seterunya korang kena setup user agent
* korang buka `terminal` tadi dan `view page source` page tersebut
* seterusnya korang buka `inspect element` page tu macam gambar bawah

![28](https://user-images.githubusercontent.com/23289982/205311973-95ba8367-7665-451f-a0c8-46bb5496bef3.png)

* korang click `3 dot ` > `more tools` > `network condition` untuk setup user agent

![29](https://user-images.githubusercontent.com/23289982/205312565-a00f05a8-0099-4512-ab42-164fc3e4013b.png)

* korang akan dapat satu tab `network conditions` > untick `use browser default` > replace md5 tadi ke ruangan tu seperti gambar
* korang just refresh saja page tu atau tekan `F5`
* jengjengjeng korang akan dapat final flag
* korang submit sahaja flag tersebut dan korang akan dibawa ke page terakhir

![image](https://user-images.githubusercontent.com/23289982/205313926-bfe38359-7956-4e6f-81fc-1513e6050fc3.png)

* ini adalah page terakhir, Tahniah buat korang yang berjaya sampai kesini.
# THE END!
