# CyberRangeᶜᶻ Platform D3 Service

This library serves as a wrapper for D3 and D3 types imports for better developer experience in Angular environment. You can inject the service into any component or service.

## Usage

Install the library with `npm install @crczp/d3-service`

Import the service and other D3 types you wish to use like this

`import {D3, D3Service, ScaleBand, ScaleLinear} from '@crczp/d3-service';`

Define your attribute like this

`private readonly d3: D3;`

Add dependency injection into constructor of your component or service like this

```
  constructor(d3Service: D3Service) {
    this.d3 = d3Service.getD3();
  }

```
