# GT-NCSU NSF-DMREF Website Repository

This repository hosts and maintains the research website for the NSF-DMREF Award (#2324190) jointly led by Georgia Tech and NCSU. It serves as a central hub for sharing project updates, team member information, research outputs, data, and tools. The goal is to provide a transparent and organized platform for collaborators, funding agencies, and the broader scientific community to stay informed about ongoing work and outcomes.

The project is part of the NSF's **Designing Materials to Revolutionize and Engineer our Future (DMREF)** initiative and focuses on advancing fundamental knowledge related to materials design and processing through advanced testing methodology, theory, computation, and leveraging machine learning and data mining towards accelerated materials discovery in the organic semiconductor field; and we are addressing current challenges in polymer semiconductor materials discovery. This combination of theory, automated experimentation, detailed structural characterization, and machine learning approaches will enable predictive tools of this complex space to be realized. 

> This documentation is primarily intended for the maintainer of the website repository.  
> If you are a project member or contributor, feel free to browse the code and open issues or pull requests.  
> For write access or major updates, please contact the maintainer.

---

## Maintainer

- Zhihao Feng (zfeng77@gatech.edu) (Maintainer since 2025)

---

## Repository Overview

This repository powers a static website and includes content and data related to:

- Research Projects
- People (PIs & Students)
- Publications
- Data
- Tools & Resources

---

## Website Structure

The website consists of the following major sections:

- **Home**
- **Research Projects**
  - Ongoing Projects
  - Collaborations and Affiliations
- **People**
  - Current Members
  - Previous Members
- **Publications**
- **Data**
- **Tools**

---

## How to Update Sections

### 1. Research Projects
- Navigate to the `projects/` folder or `projects.html` file depending on your setup.
- Add new project entries using the existing format.
- Include title, collaborators, abstract, and links to relevant papers or datasets.

### 2. Publications
- Publications are typically stored in a `publications.html` or similar Markdown/HTML/JSON file.
- Maintain chronological order.

### 3. People
- Update `people.html` or its corresponding folder.
- For each member, include:
  - Name, position/title, email, photo, and short bio or research interest.

### 4. Data
- Upload datasets to a `data/` folder or link to external repositories.
- Include README files describing dataset content and usage.

### 5. Tools
- Add developed software or scripts under the `tools/` section.
- Provide basic documentation, GitHub links, and example usage.

---

## Deployment Notes

- For Vercel deployment as a free static site:
  1. Connect your GitHub repository to Vercel.
  2. Select the appropriate root directory (e.g., `/`, `/docs`, `/public`).
  3. Customize your domain or use the default Vercel subdomain.

---

## License

To be determined.

---

## Acknowledgments

This work is supported by the National Science Foundation under Grant No. **DMREF-2324190**. We thank all project collaborators across Georgia Tech, NCSU, and partnering institutions.
