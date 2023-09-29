# Project Title

Creating an AM Radio Receiver Using GNU Radio and RTL-SDR

## Overview

This project aims to build an AM radio receiver using GNU Radio and an RTL-SDR dongle. The objective is to receive and demodulate AM radio signals, allowing users to tune into different AM radio stations and visualize the signal spectrum using waterfall and FFT plots.

## Hardware and Software Requirements

**Hardware:**

- RTL-SDR dongle with USB antenna
- Computer with GNU Radio installed
- Speakers or headphones for audio output

**Software:**

- GNU Radio Companion (GRC)

## Installation

1. Connect RTL-SDR dongle to computer.
2. Launch GNU Radio Companion (GRC).
3. Open the provided flowchart file or create a new one based on the project's specifications.
4. Configure the flowchart blocks, ensuring that you set the correct parameters for your RTL-SDR dongle, such as the device arguments, sample rate, and gain.
  ![RTL-SDR_Source_Block](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/8b3d805a-9495-4e0a-9783-5750801621a6)
  ![Signal_Source_Block](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/f6a90703-5e0c-4a50-a5ef-451d8c6f8e20)
  ![Label_Blocks](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/03e6ac04-a386-4d8e-bf02-ee4864826612)
  ![AM_Demod_Throttle_RR_Audio_Sink_Blocks](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/fccbb1ec-3ae5-4327-a884-c0ce3df523a6)
  ![QT_GUI_Waterfall_Sink_Block](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/5313f486-55fe-49b1-9f59-57e54eb2e24a)
  ![QT_GUI_Freq_Sink_Block](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/035b0fde-9e60-414c-9358-3f8529930e8d)
  ![Multiply_LPF_Block](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/b71b1549-c48b-413e-8a7f-e68af34c3f26)

6. Connect the flowchart blocks as described in the project documentation.
7. Save your GNU Radio flowchart.

## Usage

1. Run the saved GNU Radio flowchart by clicking the "Execute" button in GNU Radio Companion.
2. Adjust the controls, such as frequency, gain, and bandwidth, to tune into different AM radio stations.
3. Observe the waterfall and FFT plots to visualize the signal spectrum.
4. Use the audio output (speakers or headphones) to listen to the demodulated AM radio broadcast.

## Flowchart Diagram

![image](https://github.com/griffinwiley/ENEE_4141_Digital_Comms/assets/88199870/7ba20c8e-309c-49f3-89e9-f4752e1fef4d)

## Results

The project successfully creates an AM radio receiver using GNU Radio and RTL-SDR. Users can tune into various AM radio stations and visualize the signal spectrum. The demodulated audio allows for listening to AM broadcasts with clarity.


## Contact

For questions or support, please contact Griff Wiley at griffinwiley@gmail.com

Feel free to replace "[Your Name]" and "[Your Email Address]" with your actual name and contact information. Additionally, include the flowchart diagram or screenshot in the "Flowchart Diagram" section when you're ready to share it on GitHub.
