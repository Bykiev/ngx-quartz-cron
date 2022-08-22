# Quartz/Unix Cron Component - Angular

[Angular](https://angular.io/) cron widget built from the ground up using only [Bootstrap 4](https://getbootstrap.com/) CSS.

## Getting Started

This is an open source project that builds a cron builder component for Angular applications.
It supports Quartz/Unix cron string formats for both input and output.
Inspired by this [non-angular](https://www.freeformatter.com/cron-expression-generator-quartz.html) implementation.

## Installation


## Display the cron component
You need to import the QuartzCronModule that you want to display by adding the following lines to your ngModule.

```
import { QuartzCronModule } from '@sbzen/ng-cron';

@NgModule ({
  imports: [QuartzCronModule]
})
```
Add the cron component into yout template
```
<quartz-cron></quartz-cron>
```

## Compatibility
The only two required dependencies are Angular and cron-core.
The Bootstrap CSS is optional as you can use this component with your own styling.
Here is the versions compatibility list:

| ngx-quartz-cron  |    Angular    |  Bootstrap CSS |
| -------------    | ------------- | -------------- |
| >=2.0.0            | 14.x.x        | 4.x.x          |
