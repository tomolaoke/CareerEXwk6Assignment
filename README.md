***Test with Postman***

**Use Postman to test each endpoint:**

GET /drugs/antibiotics: http://localhost:3000/drugs/antibiotics

GET /drugs/names: http://localhost:3000/drugs/names

POST /drugs/by-category: http://localhost:3000/drugs/by-category

Body: { "category": "Antibiotic" }


GET /drugs/names-manufacturers: http://localhost:3000/drugs/names-manufacturers

GET /drugs/prescription: http://localhost:3000/drugs/prescription

GET /drugs/formatted: http://localhost:3000/drugs/formatted

GET /drugs/low-stock: http://localhost:3000/drugs/low-stock

GET /drugs/non-prescription: http://localhost:3000/drugs/non-prescription

POST /drugs/manufacturer-count: http://localhost:3000/drugs/manufacturer-count

Body: { "manufacturer": "Pfizer" }


GET /drugs/count-analgesics: http://localhost:3000/drugs/count-analgesics
