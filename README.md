# Pharmacy-System
The Pharmacy System project addresses the potential adverse interactions between different drugs and their impacts on diseases. It aims to provide healthcare professionals with information to make informed prescription decisions.

## <img width="20" height="20" src="https://img.icons8.com/dotty/80/41b883/overview-pages-2.png" alt="overview-pages-2"/>
In this project, you will find four different datasets, each containing the following information:

- **Dataset 1**: Contains information about drug names and their prices.
- **Dataset 2**: Contains the names of existing diseases.
- **Dataset 3**: Contains the names of each drug, a list of effective drugs, and the type of their adverse effects. If no effect is specified, it implies a positive effect, where no distinction is made between positive and neutral effects.
- **Dataset 4**: Contains drug sensitivities for diseases. The dataset lists drug names along with their positive or negative effects on specific diseases. Drugs with no effects on diseases are not listed.

The project's goal is to design a system that analyzes and displays information about drugs, diseases, interactions, and the effects of drugs on diseases. This system assists physicians in making optimal prescription choices.

## <img width="20" height="20" src="https://img.icons8.com/ios/50/41b883/gears--v1.png" alt="gears--v1"/> Implemented Functions

The program should offer the following functionalities for healthcare professionals:

1. **CRD Operations**: Ability to create, read, and delete drug entries based on Dataset 1, with their effects applied to Datasets 3 and 4.
2. **Cascade Delete Effects**: When a drug is deleted, its effects should cascade through Datasets 1, 3, and 4.
3. **CRD Operations for Patients**: Ability to manage patient entries with drug effects on diseases, based on Dataset 2 and applied to Dataset 4.
4. **Cascade Delete Patients**: When a patient is deleted, their effects should cascade through Datasets 2 and 4.
5. **Search**: Search for drugs and diseases individually.
6. **Display Drug Effects**: Enter a drug name and see its effects on diseases, along with the adverse effects of other drugs.
7. **Display Positive Effects**: Enter a disease name and display drugs with positive effects for its improvement.
8. **Price Adjustment**: Adjust drug prices collectively based on the inflation rate. Inflation rate is entered manually as input.
9. **Random Interactions**: When adding a new drug, randomly select a number of existing drugs from Dataset 1 and specify their adverse effects randomly for the new drug. Also, randomly select a number of diseases from Dataset 2 and assign positive or negative effects randomly for the new drug in Dataset 4.
10. **Random Patient Effects**: When adding a new disease, randomly select a number of drugs from Dataset 1 and assign positive or negative effects randomly for the new disease in Dataset 4.

## <img width="20" height="20" src="https://img.icons8.com/ios/50/41b883/hint.png" alt="hint"/> User Interface

- The program utilizes a console-based user interface.
- Real-time execution duration of each command is displayed in microseconds.
