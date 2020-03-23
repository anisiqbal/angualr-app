Structuring Angular App:

| src
    | app
        | components +
            | new-component +
            |
        | core +
            | http +
                | service-name +
                | service-name +
                |
            | services +
                | service-name +
                | service-name +
                |
        | shared-components +
            | new-component +
            |
        | layout +
            | header +
            | footer +

> http - api calls
> services - data sharing between components

Create new component
- open components folder in terminal
> ng generate component component_name

Create new service
- open services folder in terminal
> ng generate service service_name