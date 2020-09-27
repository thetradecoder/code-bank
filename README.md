# code-bank
A simple document page to code flashback to refresh the memory whenever needed

## Post data with axios
```
const dataToSend = {
field1:'value1',
field2:'value2'
}
axios.post('url-here', dataToSend)
.then(d=>window.alert('submitted'))
.catch(err=>window.alert('submission failed'))
```
## Get data with axios
```
axios.get('url-here')
.then(res=>{
let data = res.data;
// do something with data
})
.catch(err=>console.log(err));
```

## Update data with axios (put)
```
const updateData = {
field1:'updated f1 value',
field2:'updated f2 value'
}

axios.put('url-here', updateData)
.then(d=>window.alert('updated'))
.catch(err=>window.alert('update failed'))
```
## Delete data with axios 
```
const id = 'id-to-delete....';
axios.delete(`url-here/${id}`)
.then(d=>window.alert('deleted'))
.catch(err=>window.alert('failed'))
```
