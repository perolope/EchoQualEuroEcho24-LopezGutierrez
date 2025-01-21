# Echocardiography Image Quality Assessment:  
**Human Subjectivity and Artificial Intelligence Prediction in Multi-Centre Data**

## Authors
P. Lopez-Gutierrez, A. Morales, L. Dux-Santoy, J. Garrido-Oliver, H. Majul, L. Rivas Catoni, S. Martin Grieve, G. Prado, J. Solsona, G. Casas-Masnou, G. Teixido-Tura, L. Galian-Gay, I. Ferreira-Gonzalez, J. Rodriguez-Palomares, A. Guala  
**Affiliation**: University Hospital Vall d'Hebron, Barcelona, Spain

## Abstract
Echocardiography image quality is crucial for accurate care, but its assessment is often subjective. This study explores:
1. The key features influencing perceived image quality.
2. AI-based metrics to quantify these features.
3. Variability of AI performance across centers.

## Study Objectives
- **Identify Key Features**: Understand features driving image quality.
- **Develop AI Metrics**: Train AI models to predict quality metrics.
- **Assess Variability**: Evaluate model performance across multiple datasets.

## Methods
- **Data Sources**:  
  - 15,000 anonymized transthoracic echocardiograms (TTE) from Vall d’Hebron Hospital (VH).  
  - 1,000 videos from CAMUS database.
- **Quality Metrics**:  
  1. **Border Definition**: Clarity of structure borders.  
  2. **Structure Completeness**: Presence of all expected cardiac structures.  
  3. **Foreshortening**: Apical foreshortening assessment.
- **Annotation**:  
  - 6,831 VH videos annotated by cardiologists.  
  - 1,000 CAMUS videos annotated using pre-existing metrics.
- **AI Training & Validation**:  
  - **Training**: 5,256 videos from VH.  
  - **Validation**: 1,424 VH videos and 1,000 CAMUS videos.

## Results
1. **Human Subjectivity**:  
   - Inter-observer agreement was low in VH data:  
     - 56% (borders), 48% (structures), 46% (foreshortening).  
   - CAMUS annotations had poor agreement with VH annotations.
2. **AI Model Performance**:  
   - Internal validation (VH):  
     - Borders: 60%, Structures: 54%, Foreshortening: 53%.  
   - External validation (CAMUS):  
     - Borders: 57%, Structures: 19%.
3. **Key Insights**:  
   - Image quality depends primarily on **border definition**.  
   - BMI negatively affects border definition, reproduced by AI models.  
   - AI models generalize well for border definition but less so for structure completeness.

## Conclusions
- Echocardiography image quality is subjective and mainly influenced by border definition.  
- AI models show promise in learning quality metrics but face challenges in generalizing across centers.  
- Standardized quality metrics and diverse training datasets are essential for broader clinical application.

## Funding Acknowledgements
- PID2021-128367OA-I00  
- LCF/BQ/PR22/11920008  
- SEC/FEC-INV-CLI 24/12  
- MIA.2021.M02.0005  
- 2023 FI-1 00322  
- FORT23/00034  
- Supported by:  
  - Spanish Ministry of Science and Innovation  
  - La Caixa Foundation  
  - Spanish Society of Cardiology  
  - Generalitat de Catalunya  
  - Instituto de Salud Carlos III (ISCIII)  

## Contact
**Dr. Pere Lopez**  
Cardiovascular Imaging Department  
Vall d'Hebron Institute of Research  
Barcelona, Spain  
Email: pere.lopez@vhir.org

## Poster
Click on the poster below to view the full PDF:  
<a href="https://github.com/perolope/EchoQualEuroEcho24-LopezGutierrez/blob/main/poster_euroecho24.pdf">
    <img src="https://github.com/perolope/EchoQualEuroEcho24-LopezGutierrez/blob/main/euroechoposeter.png" alt="EuroEcho 2024 Poster" width="500">
</a>

