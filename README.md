# Hospital Cabin Management System

## Overview

This C program manages hospital cabins, allocating odd-numbered cabins to male patients and even-numbered cabins to female patients. The system maintains cabin details and handles waiting lists for when cabins are unavailable.

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

The main function provides a menu-driven interface to admit, discharge patients, and view details.

## Usage

1. **Compile**:
   ```sh
   gcc hospital_management.c -o hospital_management
