# 🧠 LearnGap AI — Learning Gap Diagnostic Engine

An AI-powered educational platform that identifies students' underlying conceptual weaknesses through diagnostic assessments, prerequisite knowledge graphs, explainable analysis, and personalized micro-learning.

**Hackathon:** MITK AI VISION 24H  
**Problem Statement:** PS-05  
**Domain:** AI/ML — Educational Technology  
**Target Users:** Students and Teachers  
**Subject:** Mathematics — Grades 6–8

---

## 🎯 Problem Statement

Traditional educational assessments identify incorrect answers but often fail to explain why students struggle.

A student who performs poorly in algebra may have difficulty with an earlier concept, such as fractions, integer operations, or inverse operations.

LearnGap AI addresses this challenge by identifying likely underlying learning gaps and recommending targeted learning activities.

## 💡 Our Solution

LearnGap AI analyzes student responses and mathematical prerequisite relationships to identify potential conceptual weaknesses.

The platform provides evidence-based explanations, interactive knowledge graphs, targeted micro-lessons, and reassessment to help students strengthen their understanding.

## ✨ Key Features

- **Diagnostic Quiz:** Assess mathematical understanding through structured questions.
- **Learning Gap Detection:** Identify likely conceptual weaknesses using explainable diagnostic rules.
- **Interactive Knowledge Graph:** Visualize mathematical concepts and prerequisite relationships.
- **Personalized Micro-Lessons:** Provide targeted explanations, worked examples, and practice questions.
- **Reassessment:** Compare performance before and after learning activities.
- **Teacher Dashboard:** Analyze student performance and identify common learning difficulties.
- **Evaluation Dashboard:** Compare predicted learning gaps with annotated student profiles.
- **Dataset Import:** Import student profiles using JSON or CSV.
- **Performance Metrics:** Calculate accuracy, precision, recall, and F1-score from available evaluation data.

## 🛠️ Technology Stack

**Frontend**
- React
- TypeScript
- Vite
- Tailwind CSS
- React Flow
- Lucide React

**Backend**
- Node.js
- Express.js
- TypeScript

**Database and Authentication**
- Supabase PostgreSQL
- Supabase Authentication (optional)

**Testing**
- Automated diagnostic and evaluation tests

## 🧩 How It Works

1. The student completes a diagnostic quiz.
2. The system evaluates the submitted responses.
3. Concept-level performance is calculated.
4. Prerequisite relationships are analyzed.
5. The engine identifies likely learning gaps and explains its findings.
6. The knowledge graph visualizes the student's learning status.
7. A targeted micro-lesson is recommended.
8. The student completes practice questions and reassessment.
9. Teachers can review student progress and evaluation results.

## 📊 Knowledge Graph

The system models relationships between foundational mathematical concepts, including:

- Basic Arithmetic
- Integer Operations
- Fractions and Rational Numbers
- Inverse Operations
- Algebraic Expressions
- Linear Equations

Concepts are classified as:

- 🟢 Mastered
- 🟡 Developing
- 🔴 Likely Learning Gap
- ⚪ Not Assessed

The diagnostic engine considers available evidence and prerequisite relationships rather than relying only on the overall quiz score.

## 🚀 Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/LearnGap-AI.git
