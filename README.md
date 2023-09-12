# IDA_Plugin_AntiDebugSeeker

## Concept

This tool was created to assist those who are new to malware analysis or are not yet familiar with anti-debugging techniques. 
Through this tool, users can automatically extract potential anti-debugging methods used by malware, making it easier for analysts to take appropriate action.

## Introduction

This is a program for automatically identify and extract potential anti-debugging techniques used by malware and displaying them in IDA.
The main functionalities of this plugin are as follows:

・Extraction of APIs that are potentially being used for anti-debugging by the malware.\n
・In addition to APIs, extraction of anti-debugging techniques based on key phrases that serve as triggers, as some anti-debugging methods cannot be comprehensively identified by API calls alone.\n

For packed samples, running this plugin after unpacking and fixing the Import Address Table is more effective.

## Installation

## Usage

## Support Functions

## About anti_debug.config

## List of detectable anti-debugging techniques


