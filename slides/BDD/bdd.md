---
theme: default
paginate: true
marp: true
color: black

footer: ''
---

![bg right:33%](https://volkanozdamar.com/images/Logo.png)
# The Story of Behavior Driven Development


## Why we need to behaviors 

---

### BDD was born to solve to triple conundurm

- Programmers didn’t want to write tests
- Testers didn’t want programmers writing tests
- Business stakeholders didn’t see any value in anything that wasn’t production code.

---

### in March 2006 , Dan North published an article in Better Software magazine

    https://www.stickyminds.com/better-software-magazine/behavior-modification


![bg left:40%](better_software.jpg)

---

My response is behavior-driven development (BDD). It has evolved out of established agile practices and is designed to make them more accessible and effective for teams new to agile software delivery.

---
# Test method names should be sentences


```java
public class CustomerLookupTest extends TestCase {
testFindsCustomerById() {
...
}
testFailsForDuplicateCustomers() {
...
}
...
}
```
CustomerLookup
- finds customer by id
- fails for duplicate customers
- ...

---

# A simple sentence template keeps test methods focused (The class should do something)

```
public class ClientDetailsValidator {
 
private final AgeCalculator ageCalc;
 
public ClientDetailsValidator(AgeCalculator ageCalc) {
this.ageCalc = ageCalc;
}
}
```