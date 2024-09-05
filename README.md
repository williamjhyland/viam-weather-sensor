# Viam Unix Socket Sensor Module
## Description

This project demonstrates the integration of a Viam weather sensor component that retrieves weather data from an external source based on a specified location. The sensor fetches weather information at a configurable interval and processes data in a buffer. Weather data, including temperature, humidity, and other relevant metrics, is parsed as JSON and printed with precise timestamps, ensuring efficient and accurate data capture for various applications.

## Viam Module

A module is a package with streamlined deployment to a Viam server. Modules can run alongside viam-server as separate processes, communicating with viam-server over different protocols. A Viam Module can deploy and manage components such as a Viam Weather Sensor.

## Viam Sensor

A sensor component sends can send information returned from the “GetReadings” method to the computer controlling the machine. We can customize capture data continuously, or only when specific conditions are met.

## Configuration

Generalized Attribute Guide
```json
{
  "location": "location string",
  "api_key": "your_api_key_here"
}
```

Generic Example
```json
{
  "location": "New York, USA",
  "api_key": "your_api_key_here"
}
```
