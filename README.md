# Hospital Cabin Management System

## Overview

The Hospital Cabin Management System is designed to efficiently manage the allocation of hospital cabins to patients. It handles the allocation of odd-numbered cabins to male patients and even-numbered cabins to female patients. In cases where cabins are unavailable, the system maintains waiting lists for male and female patients until cabins become free.

## Features

1. **Patient Admission**: Allocates cabins or adds to the waiting list if no cabin is available.
2. **Patient Discharge**: Frees up cabins and allocates them to waiting patients if any.
3. **View Patient Details**: Displays details of the patient in a specified cabin.
4. **Display Waiting List**: Shows waiting lists for male and female patients.

## Code Structure

- **Struct Definitions**: `cabin` for cabin details, `waiting` for the waiting list.
- **Functions**: 
  - `create_LL`: Initializes cabins.
  - `add_waiting`: Adds to the waiting list.
  - `admission`: Handles patient admission.
  - `discharge`: Manages patient discharge and reallocates cabins.
  - `display_patient_detail`: Shows patient details.
  - `display_waiting_list`: Displays waiting lists.

### Main Function

- Provides a menu-driven interface for users to interact with the system.
- Options include admitting patients, discharging patients, viewing patient details, and displaying waiting lists.
- Users can input their choice through a menu and the program executes the corresponding functionality.

## Usage

1. **Compile**:
   ```sh
   gcc hospital_management.c -o hospital_management

## Example Workflow
- Upon starting the program, users are presented with a menu.
- They can choose to admit a patient, discharge a patient, view patient details, or display waiting lists.
- The program handles the allocation of cabins and manages waiting lists efficiently based on user input and system status.

This Hospital Cabin Management System helps streamline the process of allocating hospital cabins, ensuring efficient patient management and utilization of resources.







