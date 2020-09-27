# code-bank
A simple document page to code flashback to refresh the memory whenever needed

## Post data with axios
```
const dataToSend = {
field1:'value1',
field2:'value2'
}
axios.post('url', dataToSend)
.then(d=>console.log('submitted')})
.catch(err=>console.log(err))
```
