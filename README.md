# git-exercise
1. Add initial README.md
2. Ini line yang salah


## A. Inisialisasi project di local & remote repository
1, Membuat remote repo di github
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/b6552f80-56ec-471a-b524-4a3102e314e5)

2. Update README.md di remote repo
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/0f73c0a7-d06b-45c1-9741-10e6e175e09f)

3. git clone git@github.com:nabiilNajm26/git-exercise.git
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/506e6550-2eae-4a6d-ad2d-73c83c919547)
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/742007b4-d2f1-4681-9183-be2f15e79c5f)

 
4. cd git-exercise
5. git remote -v
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/cff12a5c-6c65-4dbb-b104-5ac17e607470)


6. git config –list

![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/456fd7fa-1fc5-485a-830f-682c7b1e4efe)

## B. Membuat file baru di branch dan merge branch tersebut ke main
7. git checkout -b add/file
8. git branch
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/7cbc44e7-413f-4c10-ae18-28055d4e78c3)

 
9. Create 3 files, addition.py, multiplication.py, substraction.py. 
10. git status
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/d77c1eb5-a9b0-4fe6-b232-342ac59edee9)

11. git add .
12. git status
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/35a1c35b-a1d5-4136-b77f-781f371a6d82)

13. git commit -m “feat: Add addition, multiplication, and substraction functions.”
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/6f8fa0e1-6034-4b9a-8986-c9a13787953a)
 
14. Check commit graph pada GitLens
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/d2bcc0f2-81d6-4406-bf3f-fdbb0eeb26c0)

15. git log
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/f1072025-4a3e-4177-b7ed-b0a6b011271a)

16. git checkout main
17. git log
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/9e5de97a-1ce5-4711-bd1e-3541c72342d8)

18. git merge add/file 
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/a9c50f8f-3ff1-40b3-9205-9e81073f0084)

19. Check commit graph pada GitLens
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/346a2f15-103e-4357-a224-764c9309e2a8)

20. git log
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/ac2398f3-5823-444f-8757-323db25520a1)


## C. Studi Kasus Merge Conflict

21. Buat dan commit perubahan secara langsung di remote repo
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/6c997b27-8a10-4354-bec7-8925126fc2cf)

22. git checkout -b edit/readme
23. git branch
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/00ebd55a-31ff-4352-a2ed-0682eebe05a8)

24. notepad README.md
25. Edit README.md menjadi:
26. git status
27. git add .
28. git commit -m “edit: README.md”
29. git log
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/34fa08c1-33cc-4970-89d4-d031ae267389)

30. git checkout main
31. git merge edit/readme
32. git log
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/06f329a5-1fb8-4452-ad2f-24a7764833c5)

33. git pull origin main (terdapat conflict) 
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/eb1b9091-d7e0-4361-92a0-03e68a947962)
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/7f1cca1b-6d7c-48ac-8e21-af3d41c7749d)

 
34. Solve conflict
35. git log
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/5bdf3c29-fd85-4547-b6b9-15766324d587)

36. git checkout edit/readme
37. git push origin edit/readme:edit/readme
38. Compare & pull request
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/b1c33176-c121-47b9-bd44-d68a096a0ae5)

39. Create pull request
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/beff1d57-f9e9-4d84-9e42-fb1aa377cefd)

40. Ressolve conflict
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/c8db6b80-c404-4450-8d35-9a533e710fd9)
![image](https://github.com/nabiilNajm26/git-exercise/assets/99080449/d1d91deb-24a5-43c7-94d4-25a9875ddd92)

 

