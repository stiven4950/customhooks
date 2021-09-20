# useFormHook

Ejemplo de uso:
```
const initialForm = {
    name: '',
    age: 0,
    email: '',
}
const [ value, handleInputChange, clearValues ] = useForm(initialForm);
```