# Saudi Arabia: UGT × ARDL

Interactive econometric research visualization based strictly on the submitted project report.

## Run
```bash
npm install
npm run dev
```
Open http://localhost:3000

## Source discipline
- Annual Saudi Arabia data, 1992–2023, World Bank WDI.
- Reported methodology and empirical values are used as the source of truth.
- Structural breaks use the Lee–Strazicich two-break test, not Zivot–Andrews.
- The report's reported ARDL(2,1,3,2) notation is preserved without reconstructing an alternative lag ordering.
- Correlation is explicitly marked as an exploratory calculation from the reported level series, not a reported causal result.
