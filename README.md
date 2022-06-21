# currency codes JSON[zh-hans]

ISO 4217 is a standard published by International Organization for Standardization (ISO) that defines alpha codes and numeric codes for the representation of currencies and provides information about the relationships between individual currencies and their minor units. This data is published in three tables:

- Table A.1 – Current currency & funds code list[1]
- Table A.2 – Current funds codes[2]
- Table A.3 – List of codes for historic denominations of currencies & funds[3]



## 🔨 Usage
Enter the following code in the console of the website to obtain the latest currency-Codes data

```
let a = [];
Object.values(document.getElementsByTagName("tbody")[0].children).map(
  (item) => {
    a.push({
      "country": item.children[0].innerText,
      "currencyUnit": item.children[1].innerText,
      "currencyCode": item.children[2].innerText,
    });
  }
);
a;
```

## 🔗 Links

- [iban website - currency codes page](https://www.iban.hk/currency-codes)
- [wikipedia - currency codes zh-hans](https://zh.m.wikipedia.org/zh-hans/ISO_4217)
- [wikipedia - currency codes](https://en.wikipedia.org/wiki/ISO_4217)
