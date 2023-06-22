<!-- Start SDK Example Usage -->
```java
package hello.world;

import corn_test.petstore_test.PetstoreTest;
import corn_test.petstore_test.models.operations.CreatePetsResponse;

public class Application {
    public static void main(String[] args) {
        try {
            PetstoreTest sdk = PetstoreTest.builder()
                .build();

            CreatePetsResponse res = sdk.pets.createPets();

            if (res.statusCode == 200) {
                // handle response
            }
        } catch (Exception e) {
            // handle exception
        }
    }
}
```
<!-- End SDK Example Usage -->