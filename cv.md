# EVGENII AKHANTEV

### Contact information:
- E-mail: eahantev@gmail.com
- Telegram: [@sr01085](https://t.me/sr01085)
- GitHub: [@EAkhantev](https://github.com/EAkhantev)


### About myself:


### Skills:
- Python, Django Framework
- Git, GitHub, GitLab
- Docker (basic skills for implementing CI/CD in GitLab)
- HTML, CSS, JavaScript
- VSCode, Sublime
- ANSYS, ABAQUS, MSC Patran (CAE software for finite element analysis)

### Code example:
```
function binary_search(search_list, guess_numb){
   let first = 0
   let last = search_list.length - 1
   while (first <= last) {
      let mid = (first + last) / 2
      let curr_value = search_list[mid]
      if (curr_value == guess_numb) {
         return mid
      } else if (curr_value > guess_numb) {
         last = mid - 1
      } else {
         first = mid + 1
      }
   }

   return null
}
```