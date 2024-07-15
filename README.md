# Image Gallery
Language Uses: HTML, CSS, JAVASCRIPT
## ScreenShots
![Gallery](https://github.com/user-attachments/assets/c688b3ca-8cfb-4516-9dfe-c223ed273b9f)
![Gallery 1](https://github.com/user-attachments/assets/707e1c37-afba-4ba2-abc2-ea7ac2082a96)
![gallery Gif](https://github.com/user-attachments/assets/5be7147b-d2ce-4c96-893f-ba1dd3b2bec8)

JavaScript Code For User Interaction 👨‍💻
```javascript
<script>
        let scrolContainer = document.querySelector(".gallery");
        let backbtn = document.getElementById("backbtn");
        let nextbtn = document.getElementById("nextbtn");

        scrolContainer.addEventListener("wheel", (evt) => {
          evt.preventDefault();
          scrolContainer.scrollLeft += evt.deltaY;
          scrolContainer.style.scrollBehavior = "auto";
        });

        nextbtn.addEventListener("click", () => {
          scrolContainer.style.scrollBehavior = "smooth";
          scrolContainer.scrollLeft += 900;
        });
        backbtn.addEventListener("click", () => {
          scrolContainer.style.scrollBehavior = "smooth";
          scrolContainer.scrollLeft -= 900;
        });
      </script>

```
## Check Out The Website 👇

Visit The Website🌐 [Image Gallery](https://shayanshahdeveloper.github.io/Project-5-Image-Gallery/)

## Developed By Shayan Shah
Social media Handles 👉
[Linkdin](https://www.linkedin.com/in/shayan-shah-b31439296/)


