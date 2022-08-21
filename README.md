# VulHunter
This project is the supporting material of the paper titled "VulHunter: Hunting Vulnerable Smart Contracts at EVM bytecode-level via Multiple Instance Learning", including: dataset, detection results, source code, etc.

# Folder introduction

## Dataset1
The folder "Dataset1" includes 38,600 smart contract source codes in Dataset_1, and the detection results of each method.

## Dataset2
The folder "Dataset2" includes 579 Ethereum smart contract bytecodes in Dataset_2, and the detection results of each method.

## Dataset3

The folder "Dataset3" includes 13,413 Ethereum smart contract source codes in Dataset_3, and the detection results of each method.

## Dataset4

The folder "Dataset4" includes 183,710 Ethereum smart contract bytecodes in Dataset_4, and the detection results of each method.

## Dataset5

The folder "Dataset5" includes 29 smart contract source codes of well-known vulnerability events in Dataset_5, and the detection results of each method.

## Dataset_vul_num

The folder "Dataset_vul_num" includes two .xlsx files, which illustrates the number of each vulnerability in Dataset_1 and Dataset_2, respectively.

## VulHunter
The folder "VulHunter" includes part of the source code of VulHunter and its installation and usage tutorials. Also, it provides the pre-trained models on Benign:Malicious=2:1 contracts in Dataset_1 and Dataset_2. We promise to disclose all the source code when the paper is accepted.

## VulnerabilityMapping
The folder "VulnerabilityMapping" includes the mapping of vulnerabilities detected by methods.

## Opcodes
The folder "Opcodes" describes the Ethereum opcodes in detail.

## Severity_assessment
The folder "Severity_assessment" details contract vulnerability assessment method and its judgment basis.

## Vulnerability_examples
The file "Vulnerability_examples" depicts the 30 kinds of vulnerabilities involved in the paper, and combines the contract code to explain the vulnerability examples excepting the paper in terms of occurrence principle, severity, repair countermeasures, and insights at bytecode level.