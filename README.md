# Pastito-Product-Card

Este es un paquete de pruebas de despliegue en NPM


### Patricio Zienka Hogan

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'pastito-product-card';
```

```
 <ProductCard 
        product={ product } 
        initialValues={{
            count: 4,
            maxCount: 10
        }}
    >
        {
            ({ reset, count, increaseBy, maxCount,  isMaxCountReached }) => (
              <>
                <ProductImage  />
                <ProductTitle  />
                <ProductButtons />
              </>
            )
        }
    </ ProductCard>
    ```