# Final_Exam_DENICKA
# Final Exam Practical - ITDI204 Cloud Computing

## Student information

**Student name:** *Denicka TJIOBANG*

**GitHub repository URL:** *(https://github.com/Deni-tjiobang/Final_Exam_DENICKA.git)*

**Render application URL:** *(https://final-exam-denicka.onrender.com)

---

## Application information

**Application name:** *Final Exam - Denicka TJIOBANG*

**Render project name:** *Final Exam - Denicka TJIOBANG*

**Branch used for production deployment:** **main**

**Staging branch name:** **staging**

---

## Deployment configuration

**Build command:** **npm install**

**Start command:** **npm start**

**Environment variable MSG:** **Final Exam**

**Environment variable ENV:** **Production**

---

## API endpoints to test

### Presentation endpoint

**URL:** *(https://final-exam-denicka.onrender.com/presentation)*

**Expected result:** *Final Exam - Production*

### Correction endpoint

**URL:** *(https://final-exam-denicka.onrender.com/correction)*

**Error after first call:** *Cannot GET /correction*

**Expected result after correction:** *Correction endpoint is working*

---

## Error detection
app.get('/correction', (req, res) => {
  res.sen('Correction endpoint is working');
});...the error is the sen_ command.

**Explanation:**  
The sen error is being treated as undefined 
