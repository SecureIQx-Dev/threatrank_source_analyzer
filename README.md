# Vulnerability Analyzer

A professional tool for analyzing code vulnerabilities and security issues.

## Installation

### Step 1: Install Dependencies

Install the required Python packages into your environment:
```bash
pip install tiktoken requests networkx tqdm google-genai pandas pyyaml cryptography numpy onnxruntime transformers tree-sitter-languages
```

### Step 2: Build the Executable

Run PyInstaller on the main script:
```bash
pyinstaller vulnerability_analyzer.py
```

> **Note:** You can make changes directly to `vulnerability_analyzer.py` to modify the analysis logic before building.

### Step 3: Replace the Executable

Replace `vulnerability_analyzer_pro` with the built executable:
```bash
cp ~/dist/vulnerability_analyzer/vulnerability_analyzer vulnerability_analyzer_pro
```

The output executable should be located at `~/dist/vulnerability_analyzer/`

---

## Customization

To customize the analyzer's behavior:

1. Edit `vulnerability_analyzer.py` with your desired changes
2. Rebuild using PyInstaller (Step 2)
3. Replace the executable (Step 3)