# bdrive
Gdrive, but using blockchain :)

## Features:
- [x] **BCoin**: bdrive's own cryptocurrency for transactions on the platform
- [x] **Wesite Front End**: Website for bdrive
- [ ] **Splitting**: Split the "to-be uploded" file into smaller parts for easier upload to IPFS
- [ ] **Encryption**: Encrypt the different parts of the file sperately
- [x] **IPFS - Upload**: Upload all files to IPFS
- [ ] **Assign Hard Drives**: Assign different parts of file to different hard drives
- [ ] **IPFS - Download**: Download parts on hard drive
- [ ] **Payment**: Pay through BCoin

## Made By:
[Anirudh Emmmadi](https://anirudhemmadi.com)

[Sanjeev Penupala](https://www.linkedin.com/in/sanjeev-penupala/)

[Vihas Gowreddy](https://www.linkedin.com/in/vihas-gowreddy-550499171/)

[Anirudh Kantareddy](https://www.linkedin.com/in/anirudh-kantareddy-b3529116b/)

### For Proof of Hack 2018 Hackathon

## The Vision
Our vision for this project was to be able to securely store files on blockchain with little payment possible. 
- Two users:
  - Renter: Rents out his spare hard drive to bdrive to store files and in turn gets commission.
  - Rentee: Looking to store files somewhere else, and pays for bdrive services

- Rentee uploads file through our program
- We split the file, encrypt each part and upload to IPFS (smaller the file the more easy the upload will be)
- Assign different parts to different renters for optimal file distribution (this way rentee will be able to download their files back even when few renters are down, decentralized - files are not stored in one centralized hard drive)
- Download the uploaded parts using the "Renter" program, where renters download the uploaded parts from IPFS 
- No renter will be able to peek at the file as it is encrypted and is only a part of the whole file
- Rentee sets his settings on how long to store the file, this is used to generate the payment receipt for rentee. 
- Payment is based on time, size of the file, and available renters. All payments need to be done in BCoin. 
- Renters get commission (10% ?) through bdrive from the payment from rentee 
