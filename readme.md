# CC-Map

Literally just a map of country codes to country names.

I just don't want to copy paste it in multiple projects, ok?

## Usage

```go
countryCode := "us"
country, found := GetCountry(countryCode)
if !found {
    log.Println("country does not exist")
}
fmt.Printf("country code %q is for %q"\n, countryCode, country)
```