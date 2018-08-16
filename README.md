# Kinito.Revolution.Sql

Kinito Revolution SQL project description:

The reason is to have a `proof of concept` using the primitive capabilities of `object oriented programming` of the statistical language `R`.

In theory, it should be able to connect to any `database type` or feed on any `text file` coming from any of those.

# MS SQL Server `SqlToXlsToR`

Each BD type has its own specefications, in this case the use MS SQL Server. We are using the `ODBC Connector` to ineract with it.

## MS SQL Server `ODBC` setup

| Step | Operation                                        | Image                                                                                                             |
| ---- | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| 1    | Create a System ODBC                             | ![IMG_SqlToXlsToR_MS-SQLServer_1](https://1.bp.blogspot.com/-rn0UkuRCH9Q/V6n-Zht1QPI/AAAAAAAAAqQ/siXDSPCR8VoFh0ctWZhBJ1yQYkGcfm_PQCLcB/s400/image001.png "SqlToXlsToR MS-SQLServer_1") |
| 2    | To be used locally                               | ![IMG_SqlToXlsToR_MS-SQLServer_2](https://4.bp.blogspot.com/-3V1BOXL_da8/V6n-61Z-khI/AAAAAAAAAqY/PiOTEfeNa5k7RmS4bPG3hLNqQZ7Zjjk9wCEw/s400/image004.png "SqlToXlsToR MS-SQLServer_2") |
| 3    | In your system                                   | ![IMG_SqlToXlsToR_MS-SQLServer_3](https://1.bp.blogspot.com/-bnrViLFLBhM/V6n-ljERWsI/AAAAAAAAAqU/-bsABkxgOpIaOubDo53ysJCCJGgAFYamQCLcB/s400/image003.png "SqlToXlsToR MS-SQLServer_3") |
| 4    | With the correct user, password & ANSI compliant | ![IMG_SqlToXlsToR_MS-SQLServer_4](https://2.bp.blogspot.com/-HD0gzn5xcTo/V6oCm0DV2fI/AAAAAAAAAqo/MLkSgrdokPEiN1ucG7GL-jR8txvv-0H9wCLcB/s400/image005.png "SqlToXlsToR MS-SQLServer_4") |
| 5    | Set log paths                                    | ![IMG_SqlToXlsToR_MS-SQLServer_5](https://4.bp.blogspot.com/-LPO3AVIJguU/V6oC0l9vMBI/AAAAAAAAAqs/dsiTaxvRwrwepAsRP3cmi8Vzyxx_hC3XgCLcB/s400/image006.png "SqlToXlsToR MS-SQLServer_5") |
| 6    | Get summary                                      | ![IMG_SqlToXlsToR_MS-SQLServer_6](https://2.bp.blogspot.com/-IecvbNG8esc/V6oC6wqz5ZI/AAAAAAAAAqw/CNh5BQe4o3UUTiV5vjvsUW38ZeWbzfcowCLcB/s320/image007.png "SqlToXlsToR MS-SQLServer_6") |
| 7    | Test ODBC                                        | ![IMG_SqlToXlsToR_MS-SQLServer_7](https://1.bp.blogspot.com/-vnIZdakx3Q4/V6oDM6RkzCI/AAAAAAAAAq0/sBdjdr7D0kAuJ1ECGJKx-4SaIEOVseOkACLcB/s400/image008.png "SqlToXlsToR MS-SQLServer_7") |

## MS SQL Server `object types`

![IMG_SqlToXlsToR_MS-SQLServer_sys.object.types](SqlToXlsToR/Doc/MS-SQLServer_sys.object.types.png "SqlToXlsToR MS-SQLServer_sys.object.types")

## MS SQL Server Script `SqlToXlsToR/Script.R`

This script `Script.R` works as anchor to find the correct project and calling any program `SqlTo{Csv,Xls}ToR.R`.

```
Solution .....   Kinito.Revolution.Sql
Namespace ....   Kinito.Revolution.Sql.SqlToXlsToR
Path new .....   E:/Disk_X/Kinito.Revolution.Sql/SqlToXlsToR
```

![IMG_SqlToXlsToR_Kinito.Revolution.Sql.Script](SqlToXlsToR/Doc/Kinito.Revolution.Sql.Script.png "SqlToXlsToR Kinito.Revolution.Sql.Script")

## MS SQL Server Scripts `SqlToXlsToR/Src`

Specific scripts for `MS SQL Server` information.

```
sourcePath ...   E:/Disk_X/Kinito.Revolution.Sql/SqlToXlsToR/Src
```

### MS SQL Server Script `SqlToXlsToR/Src/SqlToCsvToR.R`

```
sourceFile ...   E:/Disk_X/Kinito.Revolution.Sql/SqlToXlsToR/Src/SqlToCsvSqlServer.R
```

### MS SQL Server Script `SqlToXlsToR/Src/SqlToXlsToR.R`

```
sourceFile ...   E:/Disk_X/Kinito.Revolution.Sql/SqlToXlsToR/Src/SqlToXlsSqlServer.R
```
