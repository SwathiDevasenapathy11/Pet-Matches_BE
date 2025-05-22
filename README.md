**Project Title:** AI-Powered Pet Breed Identifier Website

**Project Summary:**
Build a simple AI-powered website that allows users to upload an image of a pet (dog or cat) and receive an AI-generated breed prediction. The system will utilize Hugging Face's free-tier Inference API with pre-trained image classification models.

---

**Tech Stack:**

* **Frontend:** Angular 17 (Standalone)
* **Backend:** Spring Boot (Java)
* **AI Platform:** Hugging Face Inference API (Free Tier)
* **Hosting (optional):** Firebase (for frontend), Render or Railway (for backend)

---

**Free API Platform Used:**

* **Hugging Face Inference API**
  Website: [https://huggingface.co/inference-api](https://huggingface.co/inference-api)

  Model Suggestions:

  * [amaye15/ViT-Standford-Dogs](https://huggingface.co/amaye15/ViT-Standford-Dogs)
  * [espejelomar/fastai-pet-breeds-classification](https://huggingface.co/espejelomar/fastai-pet-breeds-classification)

  API Key Required: Yes (free signup)
  Rate Limit: 4,000 requests/month (Starter tier)

---

**User Experience (UX Flow):**

🐾 **User Journey on AI-PetMatch (as a user)**

🔸 **Step 1: Visit the Website**
You land on a clean, welcoming homepage with the title:
**“Find Your Perfect Pet Match with AI 🐶🐱”**
There's a big button: **“Start My Match”**

🔸 **Step 2: Take the Pet Match Quiz**
You're taken to a fun and interactive quiz where you answer about:

* 🌍 **Living Situation** – Apartment, house, with yard, etc.
* 🕒 **Work Schedule** – At home, 9–5 job, night shifts, etc.
* 🚶‍♂️ **Activity Level** – Active, occasional walks, sedentary
* 💸 **Budget for Pet Care** – Low, medium, high
* 🤧 **Allergies?** – Yes or No
* 👨‍👩‍👧‍👦 **Household Type** – Kids, elderly, other pets
* 🧠 **Personality** – Quiet, outgoing, nurturing, fun-loving

🔸 **Step 3: AI Processing**
Once you click **“Find My Match”**, the AI processes your responses behind the scenes and gives results in a few seconds.

🔸 **Step 4: View Your AI Match Result**
You’re shown a beautiful result screen:

* 🎉 **“Your Perfect Match is: Cavapoo – The Low-Shed Companion!”**
* 🐾 Based on your lifestyle and preferences, this breed is affectionate, low-maintenance, allergy-friendly, and great with kids!

You also see:

* Image of the pet breed
* Personality traits
* Care needs (exercise, grooming, vet visits)
* Pros & cons
* Option to **“Explore More Breeds”**

🔸 **Step 5: Additional Smart Features**

* ✅ **Ask AI:** “Why is this a good match for me?”
* 🗺️ **Find Nearby Clinics** (optional)
* 📜 **Pet Care Tips** generated based on your quiz result
* ❤️ **Save your result by logging in**

🎁 **What You Get as a User:**

* ✔ A personalized pet breed recommendation
* ✔ AI-generated explanation tailored to your life
* ✔ Breed comparison (optional)
* ✔ Helpful content: care tips, local suggestions, vet info (optional add-ons)
* ✔ Friendly UX that feels like a smart pet advisor

---

**Future Enhancements (Optional):**

* Let user select dog/cat before uploading.
* Save uploaded image and result to history (if login is implemented).
* Allow breed search by name with AI facts.
* Add quiz-based matching logic.

---

