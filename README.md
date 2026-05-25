# Singapore Trip Document Organizer

A single-page travel document dashboard for the Patel family Singapore trip (June 2026).

## Features

- Flights, hotels, attraction tickets, and expense summary
- Search and filter across all bookings
- View PDFs in a new browser tab
- Dark / light mode

## Run locally

```bash
cd singapore
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080)

## Add documents programmatically

```javascript
addDocument({
  category: 'tickets',
  title: 'Attraction name',
  date: '2026-07-01',
  amount: 0,
  currency: 'SGD',
  reference: 'CONF-CODE',
  pdfUrl: 'documents/your-file.pdf'
});
```
