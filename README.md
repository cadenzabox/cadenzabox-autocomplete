# Cadenzabox Autocomplete

## Script to include
```
<script src="https://unpkg.com/vue@2"></script>
<script src="./cadenza-autocomplete.js"></script>
<link rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css"
      integrity="sha512-10/jx2EXwxxWqCLX/hHth/vu2KY3jCF70dCQB8TSgNjbCVAC/8vai53GfMDrO2Emgwccf2pJqxct9ehpzG+MTw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer" />
```

### Tag to include
```
<cadenza-autocomplete group-by-type="true"></cadenza-autocomplete>
```

### Example on how to style elements inside autocomplete
```
<style>
    cadenza-autocomplete::part(autocomplete-in) {
        background-color: white;
    }
    cadenza-autocomplete::part(autocomplete__dropdown-h2),
    cadenza-autocomplete::part(autocomplete__dropdown__col-h5) {
        color: silver;
        text-transform: uppercase;
        font-size: 14px;
    }
</style>
```
