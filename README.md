# Cadenzabox Autocomplete

## Script to include
```
<script src="https://unpkg.com/vue@2"></script>
<script src="https://cdn.jsdelivr.net/gh/cadenzabox/cadenzabox-autocomplete/cadenzabox-autocomplete.min.js"></script>
<link rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css"
      integrity="sha512-10/jx2EXwxxWqCLX/hHth/vu2KY3jCF70dCQB8TSgNjbCVAC/8vai53GfMDrO2Emgwccf2pJqxct9ehpzG+MTw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer" />
```

### Tag to include
```
<cadenzabox-autocomplete group-by-type="true"
                      base-api-url="https://api.qa.cadenzabox.com"></cadenzabox-autocomplete>
```

### Example on how to style elements inside autocomplete
```
<style>
    cadenzabox-autocomplete::part(autocomplete-in) {
        background-color: white;
    }
    cadenzabox-autocomplete::part(autocomplete__dropdown-h2),
    cadenzabox-autocomplete::part(autocomplete__dropdown__col-h5) {
        color: silver;
        text-transform: uppercase;
        font-size: 14px;
    }
</style>
```

### Props
```
// If we use groupByType: true then we can set ordering number of each type
orderTag: string | number // default: 1 | optional
orderRelease: string | number // default: 2 | optional
orderTrack: string | number // default: 3 | optional
orderComposer: string | number // default: 4
____________________________________________________________________________
baseApiUrl: string // default: https://api.cadenzabox.com | required
acRedirectUrl: string // default: '' | required
____________________________________________________________________________
groupByType: boolean // default: false | optional
showTypeIcon: boolean // default: false | optional
uiSearchOutside: boolean // default: false | optional
uiSubmitOutside: boolean // default: false | optional
openInNewTab: boolean // default: false | optional
categoryName: string // default: '' | optional
categoryLabel: string // default: Popular tags | optional
inputSearchPlaceholder: string // default: Search here... | optional
```
