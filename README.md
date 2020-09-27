# code-bank
A simple document page to code flashback to refresh the memory whenever needed

## Post data with axios
```
const dataToSend = {
field1:'value1',
field2:'value2'
}
axios.post('url', dataToSend)
.then(d=>window.alert('submitted'))
.catch(err=>window.alert('submission failed'))
```
## Update data with axios (put)
```
const updateData = {
field1:'updated f1 value',
field2:'updated f2 value'
}

axios.put('url', updateData)
.then(d=>window.alert('updated'))
.catch(err=>window.alert('update failed'))
```
