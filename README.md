# npm
What is Node Package Manager and how does it work? 
I have used **[Roadmap.sh](https://roadmap.sh/full-stack)** to learn more about **npm**

### Infos

- [Mordern JavaScript Explained](https://peterxjang.com/blog/modern-javascript-explained-for-dinosaurs.html)
- [An Absolute Beginner's Guide to Using npm](https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm)

<iframe width="560" height="315" src="https://www.youtube.com/embed/2V1UUhBJ62Y?si=lB0KBz1jxdiG9or4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/jHDhaSSKmB0?si=BkB3euvwrqhDmEn4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Logs

### 15.01.2025
Today I started with the first steps to initialize and add a module to my Node Package Manager.
First I started with the initialize command of NPM
```bash
npm init
```
This command creates the **package.json** which **acts like your structure list** of needed modules. 
Without it, your partner could not find your used modules / dependencies.

After the init I added my first **module/dependency** which you can install with this command.
```bash
npm install <packagename> --save
npm i <packagename> --save
```
It will create you a **node_modules** folder containing your module.
After that, your **package.json** will be updated and you will see that it has created a new section called **Dependecys**.
With this section your friends can also install the same things you install.

On there empty project folder they can use this command with the package.json to create the same node_modules folder as you.
```bash
npm install
npm i
```
---