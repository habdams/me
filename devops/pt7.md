# Designing For Failure
This is simply having the mental preparedness for the inevitable, embracing it and not seeing system failure as an enemy but rather anticipate it in several ways to mitigate it in the nearest future.

There are popular patterns to design for failure:
## Retry Pattern
- Works by retying failed operations
-- Utilizes the back-off exponential method: you try once, your systems delay time will grow exponentially before retry.

## Circuit Breaker Pattern
- Design to avoid cascading failure, it monitors failure up to a certain threshold.
-- Identifies a service that is not available or fails, does somethign about it before it cascades down.

## Bulk Head Pattern
- It isolates failing service to limit the scope of a failure.

## Chaos Engineering (Monkey Testing)
*from Netflix*
- This is deliberately killing of d=services to see what happens and see study how other services are affected
