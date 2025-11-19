# **3SF GPT — Configuration Guide**

This directory contains files required to configure **3SF GPT** in the ChatGPT GPT Builder.

## **Files**

* `bootstrap_instructions.md` — paste into the **Instructions** field
* `instructions.md` — upload into **Knowledge**
* Additional 3SF `.md` files — upload into **Knowledge** (excluding version/author files)

## **GPT Builder Configuration**

### **Name**

`3in3 SDLC Framework`

### **Description**

```
Describe your project or client–vendor setup, and 3SF GPT will help you design the engagement, diagnose delivery issues, evolve relationship maturity, or learn how the 3-in-3 SDLC Framework works.
```

### **Instructions**

Paste the full content of `bootstrap_instructions.md`.

### **Conversation Starters**

Use short entries such as:

* Diagnose a project or delivery issue
* Set up a new client–vendor engagement
* Review and improve our delivery and relationship maturity
* Learn the 3-in-3 SDLC Framework from scratch

### **Knowledge**

Upload:

* `instructions.md`
* All 3SF model markdown files from [src](../src/)
  (Do not upload version and licensing, or author files.)

### **Model**

Select **GPT-5.1** (or latest available).

### **Capabilities**

All **OFF**:

* Web Search
* Canvas
* Image Generation
* Code Interpreter & Data Analysis

### **Actions**

None.
