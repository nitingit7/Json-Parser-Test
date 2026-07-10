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

## Here is the Sectional Test Json Format (For `English`, `GA`, and `Reasoning`)
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

