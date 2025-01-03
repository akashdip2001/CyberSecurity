[<img align="right" alt="automating-supply-chain-security-sboms-and" width="300" src="https://github.com/user-attachments/assets/370245dc-cd36-41e9-a0fc-3bc2f194fee8">](https://www.credly.com/badges/e0536338-418a-44c7-bae8-e4d47398f1e5/public_url) 


### Automating Supply Chain Security: SBOMs and Signatures (LFEL1007)

#### **Question 2.1**  
What is software provenance?  
✅ d. The history of a software product, including its origin, development, ownership, changes, and associated data  
❌ a. The design of a software application and its automatic build and release processes  
❌ b. The history of how many users have downloaded and installed a particular software program  
❌ c. The history of the speed and efficiency of software execution on a normalized resource  

#### **Question 2.2**  
Select all answers that apply. Which of the following are examples of provenance artifacts?  
✅ a. The build process that was used  
✅ b. Source code  
✅ c. Binaries  
❌ d. None of the above  

#### **Question 2.3**  
Who benefits from the proper implementation of software provenance?  
✅ d. All of the above  
❌ a. Organizations with internal software projects  
❌ b. Open source projects, maintainers, and users  
❌ c. Software vendors  

---

#### **Question 3.1**  
What role does commit signing play in source control for software provenance?  
✅ c. It verifies the authenticity of commits, increasing trust and security  
❌ a. It enhances the performance of Git  
❌ b. It automates the process of code review  
❌ d. It manages software dependencies  

#### **Question 3.2**  
What is the purpose of configuring Git with a signing key?  
✅ d. To include a cryptographic signature with commits for verification  
❌ a. To automatically merge code changes  
❌ b. To encrypt the Git repository  
❌ c. To enable secure login to the Git platform  

#### **Question 3.3**  
True or False? Repository security settings can help transform source control history into a provenance artifact by enforcing protections such as branch protection, approval workflows, and commit signing.  
✅ a. True  
❌ b. False  

---

#### **Question 4.1**  
What is the primary purpose of tracking direct and transitive dependencies in software development?  
✅ c. To enhance trust and security in the software supply chain  
❌ a. To optimize software performance  
❌ b. To simplify code review processes  
❌ d. To reduce the size of the software project  

#### **Question 4.2**  
Why is maintaining accurate data in dependency tracking challenging, as discussed in the chapter?  
✅ e. All of the above  
❌ a. Because accuracy is essential for software provenance  
❌ b. Software used as dependencies can change without notice  
❌ c. Many languages have many different tools for dependency management  
❌ d. As project size and complexity increase, tracking becomes more difficult  

#### **Question 4.3**  
What is the fundamental difference between direct and transitive dependencies in software development?  
✅ b. Direct dependencies are explicitly used in the codebase, while transitive dependencies are not  
❌ a. Direct dependencies are larger in size than transitive dependencies  
❌ c. Transitive dependencies are always more critical than direct dependencies  
❌ d. Direct dependencies are only found in large-scale projects  

---

#### **Question 5.1**  
What is the primary purpose of Git tags in software release management?  
✅ b. To identify and associate artifacts with specific release versions  
❌ a. To enhance code readability  
❌ c. To replace the need for commit hashes  
❌ d. To automate the release process  

#### **Question 5.2**  
True or False? It is unnecessary for users to pin their dependencies to a specific commit hash when Git tags are used for releases.  
✅ a. True  
❌ b. False  

#### **Question 5.3**  
What is the role of release signatures in the software supply chain?  
✅ c. They provide a cryptographic seal of authenticity and integrity to release packages  
❌ a. They ensure code efficiency  
❌ b. They streamline code reviews  
❌ d. They simplify dependency tracking  

---

#### **Question 6.1**  
True or False? Cosign is a GitHub Actions tool, and can’t be used on other platforms.  
✅ b. False  
❌ a. True  

#### **Question 6.2**  
True or False? You must create a different attestation for every artifact in your release.  
✅ b. False  
❌ a. True  

#### **Question 6.3**  
True or False? You should be ready for a high amount of maintenance once you get started on the software provenance journey.  
✅ a. True  
❌ b. False  

--- 