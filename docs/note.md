这是一个 springboot 应用。

似乎没啥可看的，算是一个标准的应用了。

待办清单：
```text
* src/main/java/org/springframework/samples/petclinic/Application.java
* src/main/java/org/springframework/samples/petclinic/controller/other/CrashController.java // 没啥看的。
* src/main/java/org/springframework/samples/petclinic/controller/other/WelcomeController.java // 没啥看的。
* src/main/java/org/springframework/samples/petclinic/controller/owner/OwnerController.java

+ src/main/java/org/springframework/samples/petclinic/config/cache/CacheConfiguration.java
* src/main/java/org/springframework/samples/petclinic/config/pet/PetClinicRuntimeHints.java // 这个不管了
* src/main/java/org/springframework/samples/petclinic/controller/pet/PetController.java
+ src/main/java/org/springframework/samples/petclinic/controller/vet/VetController.java
* src/main/java/org/springframework/samples/petclinic/controller/visit/VisitController.java
* src/main/java/org/springframework/samples/petclinic/dao/owner/OwnerRepository.java
+ src/main/java/org/springframework/samples/petclinic/dao/vet/VetRepository.java // 有个缓存注解 todo
* src/main/java/org/springframework/samples/petclinic/domain/other/BaseEntity.java
* src/main/java/org/springframework/samples/petclinic/domain/other/NamedEntity.java
* src/main/java/org/springframework/samples/petclinic/domain/owner/Owner.java
* src/main/java/org/springframework/samples/petclinic/domain/person/Person.java
* src/main/java/org/springframework/samples/petclinic/domain/pet/Pet.java
* src/main/java/org/springframework/samples/petclinic/domain/pet/PetType.java
* src/main/java/org/springframework/samples/petclinic/domain/vet/Specialty.java
* src/main/java/org/springframework/samples/petclinic/domain/vet/Vet.java
* src/main/java/org/springframework/samples/petclinic/domain/vet/Vets.java
* src/main/java/org/springframework/samples/petclinic/domain/visit/Visit.java
* src/main/java/org/springframework/samples/petclinic/service/pet/PetTypeFormatter.java
* src/main/java/org/springframework/samples/petclinic/validator/pet/PetValidator.java // 现在有很方便的注解了
+ src/test/java/org/springframework/samples/petclinic/model/ValidatorTests.java
+ src/test/java/org/springframework/samples/petclinic/owner/OwnerControllerTests.java
+ src/test/java/org/springframework/samples/petclinic/owner/PetControllerTests.java
+ src/test/java/org/springframework/samples/petclinic/owner/PetTypeFormatterTests.java
+ src/test/java/org/springframework/samples/petclinic/owner/VisitControllerTests.java
+ src/test/java/org/springframework/samples/petclinic/PetClinicIntegrationTests.java
+ src/test/java/org/springframework/samples/petclinic/service/ClinicServiceTests.java
+ src/test/java/org/springframework/samples/petclinic/service/EntityUtils.java
+ src/test/java/org/springframework/samples/petclinic/system/CrashControllerTests.java
+ src/test/java/org/springframework/samples/petclinic/vet/VetControllerTests.java
+ src/test/java/org/springframework/samples/petclinic/vet/VetTests.java
```
