# Atualizações do SoilData

## Atualizar terms and conditions of use 

````
curl -X PUT -d@./terms-and-conditions-of-use.html  http://localhost:8080/api/admin/settings/:ApplicationTermsOfUse
````


### Atualizar o User Guide

````
curl -X PUT -d https://docs.google.com/document/d/e/2PACX-1vQH5CGdu3xyAAgBv7RoCh4N7W8SSRGcZZdYuNzfXvFFL9pHxT2r7KDPEk1wonwR40P7Ptm9o1rcTIeS/pub http://localhost:8080/api/admin/settings/:NavbarGuidesUrl

````

### Atualizar o sodre 

````
curl -X PUT -d https://docs.google.com/document/d/e/2PACX-1vRoYhBv_Yn6RW-nPW_kchOfQnN_InQrKF3I6rCVvFqUOyjJ8JvW-mSx2jPvI-LsSD9-0IPQpqbD7O_k/pub http://localhost:8080/api/admin/settings/:NavbarAboutUrl

````

