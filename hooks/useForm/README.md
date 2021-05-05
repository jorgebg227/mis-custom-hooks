# useForm Hook

Ejemplo de uso
```
    const initialForm = {
        name: 'Nombre de la persona',
        age: 0,
        email: 'email@personal.es'
    }
    const [formValues, handleInputChange, reset] = useForm( initialForm );
```