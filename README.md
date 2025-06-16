# Sqwid API Endpoints

### What routes need to be called to get all NFTs in a collection
`https://sqwid-api-mainnet.reefscan.info/get/marketplace/by-collection/<COLLECTION_ID>/0?limit=<LIMIT>&startFrom=<START_FROM>`
	
- Replace `<COLLECTION_ID>` with the collection id : you can get collection id from [here](https://sqwid-api-mainnet.reefscan.info/get/collections/all/by/stats.items?sorting=desc&startAt=Infinity&startAtId=null&limit=8)
- Replace `<LIMIT>` with a number, `ex = 12` : limit is count of NFTs
- Replace `<START_FROM>` with a number, `ex = 0`:  startFrom is pagination

Example URL: https://sqwid-api-mainnet.reefscan.info/get/marketplace/by-collection/DF4cQ85hKBVxb1yjLzAD/0?limit=12&startFrom=0
  
  

<img width="200" alt="Screenshot 2025-06-16 at 2 56 41 PM" src="https://github.com/user-attachments/assets/9fd3b294-48de-4b19-a210-fa1ae87c1501" />

### Retrieve royalties addresses and percentages for NFT

`https://sqwid-api-mainnet.reefscan.info/get/marketplace/position/<POSITION_ID>`

- Replace `<POSITION_ID>` with position, which you can get from all NFTs collections list : [here](#what-routes-need-to-be-called-to-get-all-nfts-in-a-collection)




