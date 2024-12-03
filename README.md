# How I Passed the CKAD Exam in September 2024



After two weeks of dedicated preparation during my annual holiday, I took the Certified Kubernetes Application Developer (CKAD) exam on a beautiful afternoon two days ago. Twenty-two hours later, I received my badge and a score of 81 — a delightful surprise!

I wanted to delve into DevOps, and starting with Kubernetes seemed like a great choice. Setting a small goal, like obtaining the CKAD certification, made the study process even more enjoyable.

I’d like to share all the materials I used during my study:

1. **"Kubernetes: Up and Running"**

   This book is easy to read and understand, with example code you can follow along with as you progress.

2. **Udemy courses**

   - [Kubernetes for the Absolute Beginners — Hands-on](https://www.udemy.com/course/learn-kubernetes/)
   - [Kubernetes Certified Application Developer (CKAD) with Tests](https://www.udemy.com/course/certified-kubernetes-application-developer/)

3. **GitHub Practices**

   - [CKAD Exercises](https://github.com/dgkanatsios/CKAD-exercises)
   - [CKAD Practice Questions](https://github.com/bbachi/CKAD-Practice-Questions)

4. **150 questions and solutions**

   - [150 Questions and Solutions](https://www.cnblogs.com/peteremperor/p/12785335.html)

5. **Free practice environments**

   - [Killer Shell CKAD](https://killercoda.com/killer-shell-ckad)

6. **Linux Foundation Exam Simulators**

   When you schedule the exam, you’ll find a link to the Linux Foundation Exam Simulators. There are two simulators, each can be used and reset for 36 hours — I went through them four times. They’re much more cumbersome than the real exam, but they’re excellent for practicing time management. The key is to learn how to solve complicated questions quickly.

## Tips for Passing the CKAD Exam

As you prepare for the Certified Kubernetes Application Developer (CKAD) exam, here are some practical tips to help you succeed:

### 1. Master Vi/Vim Editor Shortcuts

During the exam, you’ll often need to edit YAML files efficiently. Knowing essential Vi/Vim commands can save you valuable time:

- **Search for a Pattern:** `/pattern`
  - Press `/` followed by the text you want to search for.
- **Go to the Beginning of a Line:** `^`
  - Press `^` in command mode to move the cursor to the start of the current line.
- **Go to the End of a Line:** `$`
  - Press `$` to move the cursor to the end of the current line.
- **Delete a Line:** `dd`
  - Press `dd` to delete the entire current line.
- **Delete a Character:** `x`
  - Press `x` to delete the character under the cursor.
- **Revert:** `u`
  - Press `u` to revert the change you just made.
- **Save and Quit:** `ZZ`
  - Press `ZZ` to save changes and exit Vim.
- **To indent a block of lines (e.g., lines 5 to 22):**
  - Type `:set number` to display line numbers, making it easier to reference specific lines. Then use the substitute command: `:5,22s/^/ <how many spaces to indent>/`
    - This command adds one or many spaces at the beginning of each line from line 5 to line 22.

### 2. Utilize Official Kubernetes Documentation

Having quick access to the official Kubernetes documentation is crucial for both practice and the real exam:

- **Kubectl Commands Reference:**
  - [kubectl Commands](https://kubernetes.io/docs/reference/kubectl/)
    - This page provides detailed information on all `kubectl` commands, including syntax and examples.
- **Kubernetes API Reference:**
  - [Kubernetes API v1.26](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.26/)
    - Use this resource to understand the structure and fields of Kubernetes API objects.

To find these resources quickly, visit [kubernetes.io](https://kubernetes.io) and search for “generated kubectl.”

### 3. Leverage ChatGPT for Concept Clarification

When you need a deeper understanding of Kubernetes concepts, AI tools like ChatGPT can be invaluable:

**Example Questions to Ask:**

- “Should `runAsUser` be specified at the pod level or the container level?"
- “Provide an example of a CronJob YAML file with every field filled in.”

Using ChatGPT can help you grasp complex topics more thoroughly, ensuring you’re well-prepared for any scenario you might encounter during the exam.

By incorporating these tips into your study routine, you’ll enhance your efficiency and deepen your understanding of Kubernetes, boosting your confidence on exam day. Good luck with your CKAD certification!
