# Step by step Spring Boot + Kotlin + Coroutines application
This is the repository containing the code of my Devoxx 2019 deepdive in into Reactive Spring with Coroutines and Kotlin Flow.

spring messenger
It contains the code of a simple distributed messenger application built step by step (one step per GIT branch):

step-1-webflux-r2dbc: Spring WebFlux with @Controller and R2DBC

step-2-webflux-functional: Router DSL and functional APIs

step-3-rsocket: RSocket

step-4-kotlin-js: Kotlin/JS

step-5-kofu: Kofu DSL

Notice that it could be updated to use RSocket for Frontend/Backend communication by leveraging rsocket-js but this requires creating the Kotlin/JS API wrapper.

Another ambitious but exciting improvement would be to have a RSocket multiplatform library exposed as an API with suspending functions and Kotlin Flow, see rsocket-kotlin#59 for more details.
