# Services 
## Definition
- function provided by the server
- one or more servers involved
- service requires hardware and software, reliability, maintenance and support
- example: email, DNS, authentication, printing

## Customer Requirements
- Infer about like or dislike
- server level agreement formed here

## Operational Requirements 
- it comes after customer requirements
- scalability consideration

## Open Architecture
- it provides open resources and well defined documentations
- closed resources is often motivated by market considerations
- open approach is advised as much as possible

## Simplicity
- the simplest approach to a service is the better

## Vendor Relations
- vendor engineers must be well communicated
- understand the future direction along with current state

## Machine Independence
- machines independent from their functions
- function names cannot be associated to machines
- services should be accessed only through other names

## Environment
- everything runs services should be in data centers

## Restricted Access 
- physical access is strictly restricted to SA (System Administrator)
- login features are restricted
- hardwares and other resources require protection

## Reliability 
- a consideration of service architecture
- service must minimize hardware and software dependency

## Single VS Multiple Servers
- Daemon: an independent service
- security performance and scalability are considered
- single machines easier to maintain
- multiple machines means independence of components

## Centralization
- one single group of SAs manages services resources
- well understanding and integration is required
- one center per region is applicable

## Performance
- keyword: slow/fast
- load testing is a way to test worst cases
- testing doesnt always gives the true picture

## Monitoring
- it is required to keep the service alive
- periodic monitoring

## Rollout
- documentation must be available
- consider future update and bugs
