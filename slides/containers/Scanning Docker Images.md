# Scanning Docker Images

In this lesson, we will learn about:

* Why do we need to scan our images?
* Practical tools that can helps us out

---

## What's inside an image?

* Our code is running inside a docker container
* What's inside the code besides our container? Let's check!

```bash
root@04c0bb0a6c07:/# dpkg -l | wc -l
190
```

* `dpkg -l` lists the packages installed in our container

* `wc -l` counts them