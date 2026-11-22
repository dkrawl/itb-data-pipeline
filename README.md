# Northern Star Shop – ETL Projekat

Northern Star Shop prodaje opermu za 20 klubova lige NSL. Marketing tim zeli da zna cije oprema se najvise prodaje i da li
rezultati na terenu uticu na prodaju.

## Rezime

Ovaj projekat predstavlja ETL pipeline koji procesuira sirove podatke, validira porudzbine i obogacuje podatke o prodaji
sa rezultatima fudbalskih utakmica, racuna prihode po kategoriji i timu, analizira prodaju nakon rezultata.
Rezultat pokretanja su sacuvani fajlovi na disku koji odgovaraju na pitanja marketing tima.

## Fajlovi zapisani na disku

1. clean_orders.parquet
2. league_table.csv
3. products.csv
4. rejected_orders.csv
5. revenue_by_category.csv
6. revenue_by_team.csv
7. sales_after_results.csv
8. summary.csv

## Izvestaj

```
summary = {
    'total_rows': 1852,
    'duplicates': 12,
    'valid_rows': 1800,
    'rejected_rows': 52,
    'total_revenue': 10045400.0,
    'files_written': 8
}
```

