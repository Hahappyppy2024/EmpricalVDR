# EmpricalVDR
EmpricalVDR


## EduCollab Benchmark
EduCollab is a multi-language, multi-granularity benchmark of runnable LLM-generated web application artifacts.
It includes implementations in PHP, JavaScript, and Python, and covers project-level, requirement-level, and file-level settings. 
All artifacts are built from a shared educational collaboration scenario with aligned functionality across languages.
Each artifact is paired with executable functional tests and targeted security tests, enabling controlled evaluation of vulnerability detection, repair, and verification under comparable conditions.


1. LLM-generated project-level EduCollab artifacts, paired with functional and exploit test suites.
2. LLM-generated requirement-level EduCollab artifacts, paired with functional and exploit test suites.
3. LLM-generated file-level EduCollab artifacts, derived from project-level code and restricted to files with confirmed exploitable vulnerabilities prior to vulnerability detection and repair.


# Test enviroments for Windows:
For JS artifacts:
```
npm install
```
For PHP and Python, please install the test environment before running the tests.
```
python -m venv .venv
.venv\Scripts\activate
```

The container is being created.
