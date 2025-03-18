# AI Ethnicity Detector Testing: Research Protocol

## Project Overview
This research project aims to test the accuracy and biases of AI ethnicity detection systems by analyzing how they classify celebrity images across different ethnic backgrounds. Seven student researchers will collect and standardize celebrity photos, document demographic information, and prepare a dataset for testing.

## Materials Needed
- Computer with internet access
- Spreadsheet software (Excel, Google Sheets, etc.)
- Image processing software
- Access to reliable biographical information sources

## Step 1: Image Collection & Standardization
1. **Collect celebrity photos** from reliable sources on the internet.
   - Choose clear, front-facing images with good lighting
   - Aim for diversity in age, gender, and ethnic background
   - Select images with minimal editing/filters
   - Ensure appropriate permissions for research use

2. **Process images to a standardized format**:
   - Convert all images to JPG format
   - Ensure image quality is sufficient for AI processing (recommended: at least 300x300 pixels)
   - Crop images to focus on faces (head and shoulders)
   - Ensure consistent lighting where possible
   - Use Mac_Automator_Workflow: https://github.com/ereedsanchez/AI-Ethnicity-Tests/blob/main/Mac_Automator_workflow

3. **Name files using standardized convention**:
   - Format: [Your Initials]_image_[Number]
   - Example: If your name is Jane Smith, your files would be: JS_image_01.jpg, JS_image_02.jpg, etc.
   - Use sequential numbering starting with 01

## Step 2: Demographic Research
For each celebrity image, research the following information:
1. Full name
2. Age (current)
3. Ethnic background(s)
4. Country of origin for each ethnic background
5. Gender

Use reliable sources such as:
- Official biographies
- Verified interviews where they discuss their heritage
- Reputable biographical databases
- Academic sources

## Step 3: Data Entry
Create a spreadsheet named "AI-Ethnicity-Worksheet" with the following columns:

1. **image_file**: The standardized filename (e.g., "JS_image_01.jpg")
2. **Celebrity**: Full name of the celebrity
3. **Age**: Current age in years
4. **Ethnicity 0: 'White'**: Enter "1" if present, "0" if not
5. **Prev_country_origin_0**: Country of origin if White ethnicity is present
6. **Ethnicity 1: 'Black'**: Enter "1" if present, "0" if not
7. **Prev_country_origin_1**: Country of origin if Black ethnicity is present
8. **Ethnicity 2: 'Hispanic'**: Enter "1" if present, "0" if not
9. **Prev_country_origin_2**: Country of origin if Hispanic ethnicity is present
10. **Ethnicity 3: 'East Asian'**: Enter "1" if present, "0" if not
11. **Prev_country_origin_3**: Country of origin if East Asian ethnicity is present
12. **Ethnicity 4: 'Southeast Asian'**: Enter "1" if present, "0" if not
13. **Prev_country_origin_4**: Country of origin if Southeast Asian ethnicity is present
14. **Ethnicity 5: 'Indian'**: Enter "1" if present, "0" if not
15. **Prev_country_origin_5**: Country of origin if Indian ethnicity is present
16. **Ethnicity 6: 'Middle Eastern'**: Enter "1" if present, "0" if not
17. **Prev_country_origin_6**: Country of origin if Middle Eastern ethnicity is present
18. **Gender**: Enter "Male" or "Female"

## Data Entry Guidelines
- For mixed ethnicity individuals, mark all applicable ethnicities with "1"
- Enter only the specific country of origin for each ethnicity present (leave blank if ethnicity is not present)
- Be as specific as possible with country of origin (e.g., "Nigeria" rather than just "Africa")
- For individuals with multiple countries of origin for the same ethnicity, list the primary one or separate with commas if equally significant
- Use "Male" or "Female" for gender (not abbreviated)

## Example Entry
```
image_file: JS_image_01.jpg
Celebrity: Keanu Reeves
Age: 60
Ethnicity 0: 'White': 1
Prev_country_origin_0: England
Ethnicity 1: 'Black': 0
Prev_country_origin_1: 
Ethnicity 2: 'Hispanic': 0
Prev_country_origin_2: 
Ethnicity 3: 'East Asian': 0
Prev_country_origin_3: 
Ethnicity 4: 'Southeast Asian': 0
Prev_country_origin_4: 
Ethnicity 5: 'Indian': 0
Prev_country_origin_5: 
Ethnicity 6: 'Middle Eastern': 0
Prev_country_origin_6: 
Gender: Male
```

## Research Ethics & Considerations
1. **Respect privacy and dignity**: Though using public images, ensure respectful treatment
2. **Accuracy**: Double-check demographic information from multiple sources
3. **Acknowledge limitations**: Ethnicity is complex and self-identified; our categorizations are simplified
4. **Bias awareness**: Be mindful of selection bias in your choice of celebrities

## Submission Requirements
Each student should submit:
1. A folder containing all standardized images
2. Their completed portion of the AI-Ethnicity-Worksheet (minimum 20 entries per student)
3. A list of sources


# AI Ethnicity Detector Testing: Research Protocol

## Project Overview
This research project aims to test the accuracy and biases of AI ethnicity detection systems by analyzing how they classify celebrity images across different ethnic backgrounds. Seven student researchers will collect and standardize celebrity photos, document demographic information, and prepare a dataset for testing.

## Materials Needed
- Computer with internet access
- Spreadsheet software (Excel, Google Sheets, etc.)
- Image processing software
- Access to reliable biographical information sources

## Step 1: Image Collection & Standardization
1. **Collect celebrity photos** from reliable sources on the internet.
   - Choose clear, front-facing images with good lighting
   - Aim for diversity in age, gender, and ethnic background
   - Select images with minimal editing/filters
   - Ensure appropriate permissions for research use

2. **Process images to a standardized format**:
   - Convert all images to JPG format
   - Ensure image quality is sufficient for AI processing (recommended: at least 300x300 pixels)
   - Crop images to focus on faces (head and shoulders)
   - Ensure consistent lighting where possible

3. **Name files using standardized convention**:
   - Format: [Your Initials]_image_[Number]
   - Example: If your name is Jane Smith, your files would be: JS_image_01.jpg, JS_image_02.jpg, etc.
   - Use sequential numbering starting with 01

## Step 2: Demographic Research
For each celebrity image, research the following information:
1. Full name
2. Age (current)
3. Ethnic background(s)
4. Country of origin for each ethnic background
5. Gender

Use reliable sources such as:
- Official biographies
- Verified interviews where they discuss their heritage
- Reputable biographical databases
- Academic sources

## Step 3: Data Entry
Create a spreadsheet named "AI-Ethnicity-Worksheet" with the following columns:

1. **image_file**: The standardized filename (e.g., "JS_image_01.jpg")
2. **Celebrity**: Full name of the celebrity
3. **Age**: Current age in years
4. **Ethnicity 0: 'White'**: Enter "1" if present, "0" if not
5. **Prev_country_origin_0**: Country of origin if White ethnicity is present
6. **Ethnicity 1: 'Black'**: Enter "1" if present, "0" if not
7. **Prev_country_origin_1**: Country of origin if Black ethnicity is present
8. **Ethnicity 2: 'Hispanic'**: Enter "1" if present, "0" if not
9. **Prev_country_origin_2**: Country of origin if Hispanic ethnicity is present
10. **Ethnicity 3: 'East Asian'**: Enter "1" if present, "0" if not
11. **Prev_country_origin_3**: Country of origin if East Asian ethnicity is present
12. **Ethnicity 4: 'Southeast Asian'**: Enter "1" if present, "0" if not
13. **Prev_country_origin_4**: Country of origin if Southeast Asian ethnicity is present
14. **Ethnicity 5: 'Indian'**: Enter "1" if present, "0" if not
15. **Prev_country_origin_5**: Country of origin if Indian ethnicity is present
16. **Ethnicity 6: 'Middle Eastern'**: Enter "1" if present, "0" if not
17. **Prev_country_origin_6**: Country of origin if Middle Eastern ethnicity is present
18. **Gender**: Enter "Male" or "Female"

## Data Entry Guidelines
- For mixed ethnicity individuals, mark all applicable ethnicities with "1"
- Enter only the specific country of origin for each ethnicity present (leave blank if ethnicity is not present)
- Be as specific as possible with country of origin (e.g., "Nigeria" rather than just "Africa")
- For individuals with multiple countries of origin for the same ethnicity, list the primary one or separate with commas if equally significant
- Use "Male" or "Female" for gender (not abbreviated)

## Example Entry
```
image_file: JS_image_01.jpg
Celebrity: Keanu Reeves
Age: 60
Ethnicity 0: 'White': 1
Prev_country_origin_0: England
Ethnicity 1: 'Black': 0
Prev_country_origin_1: 
Ethnicity 2: 'Hispanic': 0
Prev_country_origin_2: 
Ethnicity 3: 'East Asian': 0
Prev_country_origin_3: 
Ethnicity 4: 'Southeast Asian': 0
Prev_country_origin_4: 
Ethnicity 5: 'Indian': 0
Prev_country_origin_5: 
Ethnicity 6: 'Middle Eastern': 0
Prev_country_origin_6: 
Gender: Male
```

## Research Ethics & Considerations
1. **Respect privacy and dignity**: Though using public images, ensure respectful treatment
2. **Accuracy**: Double-check demographic information from multiple sources
3. **Acknowledge limitations**: Ethnicity is complex and self-identified; our categorizations are simplified
4. **Bias awareness**: Be mindful of selection bias in your choice of celebrities


## Step 4: AI Model Testing
Test each image across the following AI ethnicity detection systems:

1. **Niykel**
   - Access the Niykel ethnicity detection tool
   - Upload each image individually
   - Record the detected ethnicity results in columns labeled: "Niykel_Ethnicity_0" through "Niykel_Ethnicity_6" using the same binary system (1 if detected, 0 if not)
   - Record confidence scores (if provided) in columns labeled: "Niykel_Confidence_0" through "Niykel_Confidence_6"

2. **MiniApps.ai Ethnicity Guesser**
   - Visit miniapps.ai/ethnicity-guesser
   - Upload each image following the site instructions
   - Record the detected ethnicity results in columns labeled: "MiniApps_Ethnicity_0" through "MiniApps_Ethnicity_6"
   - Record confidence scores in columns labeled: "MiniApps_Confidence_0" through "MiniApps_Confidence_6"

3. **FairFace App**
   - Access the FairFace application
   - Upload each image following the application instructions
   - Record the detected ethnicity results in columns labeled: "FairFace_Ethnicity_0" through "FairFace_Ethnicity_6"
   - Record confidence scores in columns labeled: "FairFace_Confidence_0" through "FairFace_Confidence_6"

For each AI system:
- Take screenshots of each analysis result
- Note any difficulties or errors encountered during the testing process
- Document any additional attributes detected (gender, age, etc.)

## Step 5: Results Analysis
After completing the testing:

1. **Calculate accuracy rates**:
   - For each AI system, compare the detected ethnicity with the documented ethnicity
   - Create confusion matrices for each system and ethnicity category
   - Calculate precision, recall, and F1 scores for each ethnicity category across systems

2. **Analyze error patterns**:
   - Identify which ethnicities are most frequently misclassified
   - Note any systematic biases (e.g., consistent misclassification of particular ethnicities)
   - Analyze if age, gender, or image quality correlates with accuracy

3. **Compare model performance**:
   - Determine which AI system performs best overall
   - Identify which system performs best for specific ethnic categories
   - Note any differences in confidence scores across systems

## Submission Requirements
Each student should submit:
1. A folder containing all standardized images
2. Their completed portion of the AI-Ethnicity-Worksheet including AI detection results (minimum 30 entries per student)
3. Screenshots of all AI test results
4. A list of sources
5. A brief analysis report (1-2 pages) on findings from their sample
