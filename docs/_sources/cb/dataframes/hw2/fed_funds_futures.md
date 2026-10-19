# Dataframe: `hw2:fed_funds_futures` - Federal Funds Futures

Daily bars containing open, high, low, close, and volume data on 30-day Federal Funds Rate futures


## DataFrame Glimpse

```
Rows: 11806
Columns: 7
$ date   <datetime[ns]> 2026-10-16 00:00:00
$ symbol          <str> 'ZQ:BF J7-K7-N7'
$ open            <f64> -1.0
$ high            <f64> -1.0
$ low             <f64> -1.5
$ close           <f64> -1.5
$ volume          <u64> 22


```

## Dataframe Manifest

| Dataframe Name                 | Federal Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | GLBX.MDP3                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com                                   |
| Tags                           | Federal Reserve, Futures, Yields                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento API via Python                                                   |
| Data available up to (min)     | 2026-10-16 00:00:00                                                             |
| Data available up to (max)     | 2026-10-16 00:00:00                                                             |
| Dataframe Path                 | C:\Users\landi\Desktop\UChicago\Autumn 26\Data Pipelines\hw2-lsanborn0\_data\fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file://C:/Users/landi/Desktop/UChicago/Autumn 26/Data Pipelines/hw2-lsanborn0/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-18 17:27:09           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

