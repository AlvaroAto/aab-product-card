# AAB-Product-Card

Paquete de pruebas de despliegue en NPM

### Alvaro Arjona Belenguer

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'aab-product-card';
```

```
<ProductCard 
    product= { product }
    initialValues={{
        count: 4,
        maxCount: 10,
    }}
>  
    {
        ( {reset, count, isMaxCountReached, maxCount, increaseBy} ) => (
            <>
                <ProductImage /> 
                <ProductTitle />
                <ProductButtons />                     
            </>
        )
    }              
</ProductCard>
```