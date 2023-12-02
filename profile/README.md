# [CH2-PS266] Bangkit The Fed Project
## Designing a Deep Learning-Based Mobile Application for Egg Candling

A part of Bangkit Academy Batch 2 2023 by Google, GoTo, Traveloka


## About Us
Lorem ipsum

## Our Team
### Machine Learning Division

| Bangkit ID | Full Name | University | Profile |
| --- | --- | --- | --- |
| M123BSY1353 | Habibi Ahmadi Muslim | Politeknik Elektronika Negeri | |
| M466BSY1195 | Ahmad Ma'ruf | Universitas Sains Al-Qur’an | |
| M466BSX1032 | Brilian Herda | Universitas Sains Al-Qur’ an | |

### Cloud Computing Division

| Bangkit ID | Full Name | University | Profile |
| --- | --- | --- | --- |
| C182BSY3830 | Fathin Cahyo Ramadhan | Universitas Amikom Purwokerto | |
| C182BSY3969 | Yuntafa Ulkhaq | Universitas Amikom Purwokerto | |

### Mobile Development Dision

| Bangkit ID | Full Name | University | Profile |
| --- | --- | --- | --- |
| A182BSY2566 | Sandhya Nugraha Qusnur Aulia | Universitas Amikom Purwokerto | |
| A548BKY4459 | Zulfahmi M. Ardianto | UIN Sunan Kalijaga Yogyakarta | | 

## Documentation
### A. API
#### Endpoint
* **Login**
  * **Endpoint :** `/login`
  * **Method :** `POST`
  * **Body :** </br>
    `email` as `string`</br>
    `password` as `string`
  * **response :** </br>
    * **status code :** 200 </br>
      **body :**
      ```
      {
          "status": "success",
          "message": "Login berhasil",
          "user": {
          "idToken":
            "eyJhbGciOiJSUzI1NiIsImtpZCI6IjBiYmQyOTllODU2MmU3MmYyZThkN2YwMTliYTdiZjAxMWFlZjU1Y2EiLCJ0eXAiOiJKV1QifQ.eyJuYW1lIjoieXVudGFmYSIsImlzcyI6Imh0dHBzOi8vc2VjdXJldG9rZW4uZ29vZ2xlLmNvbS9hdmlkLWxvY2stNDA1ODE2IiwiYXVkIjoiYXZpZC1sb2NrLTQwNTgxNiIsImF1dGhfdGltZSI6MTcwMTQzNjc3OCwidXNlcl9pZCI6IkJUS2FQVWpwaU5UblVkb2hab3hhN1NONnk2cTEiLCJzdWIiOiJCVEthUFVqcGlOVG5VZG9oWm94YTdTTjZ5NnExIiwiaWF0IjoxNzAxNDM2Nzc4LCJleHAiOjE3MDE0NDAzNzgsImVtYWlsIjoiY29udG9oZW1haWxAZ21haWwuY29tIiwiZW1haWxfdmVyaWZpZWQiOmZhbHNlLCJmaXJlYmFzZSI6eyJpZGVudGl0aWVzIjp7ImVtYWlsIjpbImNvbnRvaGVtYWlsQGdtYWlsLmNvbSJdfSwic2lnbl9pbl9wcm92aWRlciI6InBhc3N3b3JkIn19.F5HpNXwjzNeHSErVK3ejkB2ZRRYNm_ckt9AFbK_q3GpUX9Wi0ChajSVTdxEhT6aUmLWypFyyzbrFRhz1hSShYB9b9GbbHG7QKiiaNPlcll4qaPoy7kqgy7tbxujleSj9QbV9inqKIoISuWPlEwWLkbVrviO-u1_OCoOFGNkQ6rvdM3LAp2jJ7fCUPxhDSu9RiVNCEYVj_trH8ZmQTL6XLrI8zs4WTyqtx57WT0uFoTN7p7bLxv4Z4WLhpobuq9zzfQ8MtEZ4FWZjbFOEklZezS7SLe2515r9bgkRpvSn4iY0ED_qGqahxq4rcnfZzch4WqJcvuSXX7THdt1T-2Utfg",
          "localId": "BTKaPUjpiNTnUdohZoxa7SN6y6q1",
          "email": "contohemail@gmail.com",
          "displayName": "yuntafa"
         }
      }
      ```
* **Register**
  * **Endpoint :** `/register`
  * **Method :** `POST`
  * **Body :** </br>
    `email` as `string`</br>
    `password` as `string`</br>
    `displayname` as `string`
  * **response :** </br>
    * **status code :** 200 </br>
      **body :**
      ```
      {
          "status": "success",
          "message": "Pengguna berhasil didaftarkan dan informasi pengguna ditambahkan ke Firestore"
      }
      ```
