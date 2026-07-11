# Json-Parser-Test
## Full Test Json Format
```json
{
  "test_type": "full",
  "title": "SSC CGL Tier 1 - Full Mock Test 01",
  "total_marks": 200,
  "marking": {
    "correct": 2,
    "wrong": -0.5,
    "unattempted": 0
  },
  "sections": [
    {
      "id": "reasoning",
      "name": "General Intelligence & Reasoning",
      "time_minutes": 15,
      "questions": [
        {
          "id": "q1",
          "text": "Which number replaces the question mark?...",
          "image": null,
          "options": ["A. 12", "B. 15", "C. 18", "D. 21"],
          "answer": 2
        }
      ]
    },
    {
      "id": "ga",
      "name": "General Awareness",
      "time_minutes": 15,
      "questions": [...]
    },
    {
      "id": "quant",
      "name": "Quantitative Aptitude",
      "time_minutes": 15,
      "questions": [...]
    },
    {
      "id": "english",
      "name": "English Comprehension",
      "time_minutes": 15,
      "questions": [...]
    }
  ]
}
```
---
## Here is the Json format for `English`
```json
{
  "test_type": "sectional",
  "title": "English Comprehension 06",
  "total_marks": 50,
  "marking": {
    "correct": 2,
    "wrong": -0.5,
    "unattempted": 0
  },
  "sections": [
    {
      "id": "english",
      "name": "English Comprehension",
      "time_minutes": 15,
      "questions": [
        {
          "id": "q1",
          "text": "Identify the segment in the sentence which contains a grammatical error:\n\nNeither the principal nor the teachers takes interest in the general welfare of the students.",
          "image": null,
          "passage": null,
          "options": [
            "Neither the principal",
            "nor the teachers",
            "takes interest in the general welfare",
            "of the students."
          ],
          "answer": 2
        },
        {
          "id": "q2",
          "text": "Rearrange the given sentences to form a meaningful paragraph:\n\nA. However, the exact date of its construction is still unknown.\nB. The Great Wall of China is one of the most famous landmarks in the world.\nC. It was built to protect the Chinese Empire from invaders.\nD. Many people believe it can be seen from space, which is a common myth.",
          "image": null,
          "passage": null,
          "options": [
            "BCAD",
            "BADC",
            "CBAD",
            "DBCA"
          ],
          "answer": 0
        },
        {
          "id": "q3",
          "text": "According to the passage, the French are most likely to:",
          "image": null,
          "passage": "Directions [Set of 3 questions]: You have a passage with 3 questions following. Read the passage carefully and choose the best answer to each question out of the four alternatives and mark it.\n\nIt is no wonder that the notion of happiness has been taken into public ownership, given the remarkable spread of spiritual malaise around the globe. Around a third of American adults and close to half in Britain believe that they are sometimes depressed. Even so, more than half a century after the discovery of antidepressants, nobody really knows how they function.\n\nWork over which individuals have little control can heighten the risk of heart disease. So-called austerity has made people sicker and driven some to death. Vastly unequal nations such as the UK and the US breed mental health problems far more than more egalitarian ones such as Sweden.",
          "options": [
            "Downplay their happiness",
            "Under report their dejectedness",
            "Downplay their dejectedness",
            "Not mentioned in the passage"
          ],
          "answer": 1
        }
      ]
    }
  ]
}
```
---

## Here is the Sectional Test Json Format (For `GA`, and `Reasoning`)
```json
{
  "test_type": "sectional",
  "title": "Reasoning Sectional Test - 01",
  "marking": {
    "correct": 2,
    "wrong": -0.5,
    "unattempted": 0
  },
  "sections": [
    {
      "id": "reasoning",
      "name": "General Intelligence & Reasoning",
      "time_minutes": 15,
      "questions": [
        {
          "id": "q1",
          "text": "Find the odd one out: Apple, Mango, Carrot, Banana",
          "image": null,
          "options": ["A. Apple", "B. Mango", "C. Carrot", "D. Banana"],
          "answer": 2
        }
      ]
    }
  ]
}
```
---

## Here is the ``Quant Sectional`` Json File
```json
{
  "title": "Quantitative Aptitude Sectional Test - 7",
  "test_type": "sectional",
  "marking": { "correct": 2, "wrong": -0.5, "unattempted": 0 },
  "sections": [
    {
      "id": "sec_quant_1",
      "name": "Quantitative Aptitude",
      "time_minutes": 15,
      "questions": [
        {
          "id": "q1",
          "text": "If $\\sin\\theta - \\cos\\theta = 0$, Find the value of $\\sin\\left(\\frac{\\pi}{2} - \\theta\\right) + \\cos\\left(\\frac{\\pi}{2} - \\theta\\right) = \\text{?}$",
          "options": [
            "1",
            "$2\\sqrt{2}$",
            "$\\sqrt{2}$",
            "0"
          ],
          "answer": 2
        },
        {
          "id": "q2",
          "text": "Find the roots of the quadratic equation: $$x^2 - 5x + 6 = 0$$",
          "options": [
            "$x = 2, x = 3$",
            "$x = -2, x = -3$",
            "$x = 1, x = 6$",
            "$x = -1, x = -6$"
          ],
          "answer": 0
        }
      ]
    }
  ]
}
```

