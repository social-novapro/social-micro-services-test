# Social Micro Services Test
Created by Daniel Kravec, on May 17, 2023

This is just a test for the future version of interact's api. basing it on mircoservices instead of monolythic. Interact may not end up using it, as it makes the codebase even more confusing.

Table of Pros and Cons of mircoservices
| Pros | Cons |
| -- | -- |
| Each service can run indepantently | Each service requires same base code |
| One service crashes, rest of apps keeps running. | Complicated error handling for 404s if service doesnt exist|
| Can deactivate one service just by turning off | Requires more docker containers to run backend
| Can use seperate mongo sections | Could complicate communitcation between services of backend |
| Can use different languages / db for different services | - |

<br>

### 1.0 (1.2023.05.17)
- installed express and organized
- Created pros and cons list