# AI, Machine Learning, and LLMs

**Copyright © Tage Bushman**

| Item | Details |
| :--- | :--- |
| **Updated** | January 4, 2026 |
| **Due Date** | Midnight before the next class meeting |

---

## Purpose
The purpose of this lab is to introduce you to the fundamentals of Artificial Intelligence, Machine Learning, and Large Language Models through hands-on activities that demonstrate how AI systems learn, generate outputs, and adapt to user input.

## Knowledge
After completing this lab, you will understand how AI systems, including LLMs and deep learning models, learn from data and apply patterns to generate predictions or responses.

---

## A. Large Language Models (LLMs)

Artificial intelligence (AI) is a way of getting computers to perform tasks that usually require human intelligence. Most modern AI learns from data; instead of being explicitly programmed, it is trained on examples to spot patterns.

1. Open **Microsoft Copilot** in your browser: [copilot.microsoft.com](https://copilot.microsoft.com/).
   *Note: Use your student account for protected access.*

2. In the text box, enter this **prompt**:
   ```text
   Write a brief cover letter for a marketing role.
   ```

3. **Question:** What was the output? 
   > *Paste the output in plain text in your answer document — NOT a screenshot.*

4. **Question:** What do you think is missing from the cover letter that was generated?
   *Hint: Think about what professionals tell you about applying for jobs. This is not the content the LLM left blank for you, but something else.*

5. Navigate to [this URL](https://f005.backblazeb2.com/file/webandsoftware-online/devops/ai/job_post.text) and copy the text. Then, type the following into Copilot:
   ```text
   Here’s the exact job post. Tailor the letter to it. 
   [Paste the job posting here]
   ```

6. **Question:** What do you notice this time? What is different from the last output?

7. Now, add specific achievements to the conversation:
   ```text
   Here are my relevant experiences and achievements. Incorporate them:
   - Managed a $1M annual budget, increasing lead quality by 30%.
   - Developed email automation strategies boosting retention by 15%.
   - Conducted A/B testing resulting in a 40% increase in conversion.
   ```

8. **Question:** How does this iteration compare to the first one?

9. **Independent Task:** Find a real job posting online. In a **single prompt**, try to get a tailored result similar to our multi-step process above.
   
10. **Question:** What was the prompt you used, and what was the output?

11. **Trip Planning:** Prompt Copilot to "Plan a 2 day itinerary in Chicago." Then refine it by adding interests (architecture, coffee, live music) and a budget.
    **Question:** Does adding more details and specifics make the output better?

---

## B. Deep Learning

Deep learning uses neural networks with many layers to learn complex patterns. We will use **Teachable Machine** to see this in action.

1. Navigate to [teachablemachine.withgoogle.com](https://teachablemachine.withgoogle.com/). Click **Get Started** > **Image Project** > **Standard image model**.

2. Rename **Class 1** to "dogs" and **Class 2** to "cats".

3. Download and extract these training files:
   - [Dogs Training Set](https://f005.backblazeb2.com/file/webandsoftware-online/devops/ai/dogs.zip)
   - [Cats Training Set](https://f005.backblazeb2.com/file/webandsoftware-online/devops/ai/cats.zip)
   - [Test Images](https://f005.backblazeb2.com/file/webandsoftware-online/devops/ai/test_images.zip)

4. Upload the 10 dog images to the "dogs" class and the 10 cat images to the "cats" class.

5. Click **Train Model**.

6. In the **Preview** column, toggle input to **ON** and select **File**.
   > ⚠️ **Note:** If you see the webcam instead of file buttons, toggle to "Webcam" and back to "File" to fix the interface bug.

7. Test the following files from the `test_images` folder and record the results:

| File Name | Dog % | Cat % |
| :--- | :--- | :--- |
| `dog_compare.jpg` | | |
| `cat_compare.jpg` | | |
| `dog_and_cat.jpg` | | |

8. **Question:** Under "Cats," upload `black_cat.jpg` and click **Train Model** again. What does the output display now? Did anything change?

---

## C. Machine Learning

Machine Learning (ML) is the core of modern AI, focusing on teaching computers to learn from data.

### Types of ML
1. **Supervised Learning:** Trained on labeled data (e.g., Spam detection).
2. **Unsupervised Learning:** Finding hidden patterns in unlabeled data (e.g., Customer segmentation).
3. **Reinforcement Learning:** Learning through rewards and penalties (e.g., Robotics).

### Common Algorithms
| Algorithm | Type | Use Case |
| :--- | :--- | :--- |
| Linear Regression | Supervised | Predicting house prices |
| Decision Trees | Supervised | Interpretable classification |
| K-Means | Unsupervised | Clustering similar data |
| Neural Networks | Both | Image & Speech recognition |

---

## D. Artificial Intelligence (AI) Recap

*   **AI** = The big idea of making machines smart.
*   **ML** = Teaching machines to learn from data.
*   **Deep Learning** = Using layered neural networks for complex tasks.
*   **LLMs** = Deep learning models specialized in language.

**Task:** Enter the following prompt into an LLM: `What are some examples of things that AI can do?`

1. **Question:** Based on the output, what are some of the more interesting ways to use AI?

---

## E. Reflection

**Question:** Reflect on your experience. How did refining prompts for an LLM compare to training a deep learning model with images? What challenges did you encounter, and how might these skills apply to your future career?
