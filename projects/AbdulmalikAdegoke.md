---
layout: project
studentName: "Abdulmalik Adegoke"
supervisorName: "Prof. Stephen McKenna"
projectTitle: "A Content-based Image Retrieval System for Assisting with Medical Diagnosis"
projectImage: "abdulmalik_cbir_input_form_page.png"

---

<hr>

## Project Description
This project investigated the implementation of convolutional neural networks (CNN) to make a content based image retrieval system. It also investigated the further optimisation of the relevant retrievals of the CBIR system and the implementation of a user interface for the users to interact with the system. As an additional feature, the project looked into the implementation of image classification abilities of the CNN to make a diagnosis suggestion system.

## Project Findings
This projects experiments found that:
- the precision of the retrieval was affected by the distribution and availability of the dataset images.
- the precision of the retrieval was also affected by the size of the feature vector being used for comparison.
- the precision of the system tends to be high for the melanoma and melanocytic nevus classes relative to the other classes.

Plus a takeaway for future optimisation of the system: the implementation of other levels of details of the feature maps- i.e. by using a different layer of the CNN to get the feature maps used for comparison so as to get more specific features used for the comparison. This will most likely improve the precision of the retrieval.

## Project Tech Stack
The languages used  for this project:
- Backend (CBIR system)- Python, Keras, Tensorflow
- Frontend- HTML, CSS, Vanilla JS, Bootstrap
- Serever side scripting- Django
- Database- SQLLite- due to localised django implementation

## Project Media
### The user interface created for the CBIR system
### The input form interface page
<!-- ![CBIR UI Form](../project_images/abdulmalik_cbir_form_page.png) -->
<img src="../project_images/abdulmalik_cbir_form_page.png" alt="CBIR UI Form" width="400"/>

<!-- ![CBIR UI input Form](../project_images/abdulmalik_cbir_input_form_page.png) -->
<img src="../project_images/abdulmalik_cbir_input_form_page.png" alt="CBIR UI input Form" width="400"/>
<br>
### The diagnosis support report page
<!-- ![CBIR UI Report_Page](../project_images/abdulmalik_cbir_report_page_.png) -->
<img src="../project_images/abdulmalik_cbir_report_page_.png" alt="CBIR UI Report_Page" width="400"/>

<!-- ![CBIR UI Report_Page](../project_images/abdulmalik_cbir_report_page.png) -->
<img src="../project_images/abdulmalik_cbir_report_page.png" alt="CBIR UI Report_Page" width="400"/>

### The diagnosis support report history page
<!-- ![CBIR UI Report_History_Page](../project_images/abdulmalik_cbir_report_history_page.png) -->
<img src="../project_images/abdulmalik_cbir_report_history_page.png" alt="CBIR UI Report_History_Page" width="400"/>
<br>
