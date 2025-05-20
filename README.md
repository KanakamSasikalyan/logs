2025-05-20T14:57:39.709512881Z 2025-05-20T14:57:39.709Z DEBUG 1 --- [studio] [           main] org.springframework.web.SimpLogging      : brokerChannel added SimpleBrokerMessageHandler [org.springframework.messaging.simp.broker.DefaultSubscriptionRegistry@1f481ec3]
2025-05-20T14:57:39.709975643Z 2025-05-20T14:57:39.709Z  INFO 1 --- [studio] [           main] o.s.m.s.b.SimpleBrokerMessageHandler     : BrokerAvailabilityEvent[available=true, SimpleBrokerMessageHandler [org.springframework.messaging.simp.broker.DefaultSubscriptionRegistry@1f481ec3]]
2025-05-20T14:57:39.711128533Z 2025-05-20T14:57:39.710Z  INFO 1 --- [studio] [           main] o.s.m.s.b.SimpleBrokerMessageHandler     : Started.
2025-05-20T14:57:39.711524113Z 2025-05-20T14:57:39.711Z DEBUG 1 --- [studio] [           main] org.springframework.web.SimpLogging      : clientInboundChannel added UserDestinationMessageHandler[DefaultUserDestinationResolver[prefix=/user/]]
2025-05-20T14:57:39.711623316Z 2025-05-20T14:57:39.711Z DEBUG 1 --- [studio] [           main] org.springframework.web.SimpLogging      : brokerChannel added UserDestinationMessageHandler[DefaultUserDestinationResolver[prefix=/user/]]
2025-05-20T14:57:40.406714633Z 2025-05-20T14:57:40.405Z  INFO 1 --- [studio] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port 10000 (http) with context path '/'
2025-05-20T14:57:40.909473657Z 2025-05-20T14:57:40.905Z  INFO 1 --- [studio] [           main] i.m.fashion.studio.StudioApplication     : Started StudioApplication in 152.998 seconds (process running for 165.74)
2025-05-20T14:57:42.009679922Z 2025-05-20T14:57:42.009Z  INFO 1 --- [studio] [io-10000-exec-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring DispatcherServlet 'dispatcherServlet'
2025-05-20T14:57:42.011280514Z 2025-05-20T14:57:42.009Z  INFO 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Initializing Servlet 'dispatcherServlet'
2025-05-20T14:57:42.011296884Z 2025-05-20T14:57:42.010Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Detected StandardServletMultipartResolver
2025-05-20T14:57:42.011304295Z 2025-05-20T14:57:42.010Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Detected AcceptHeaderLocaleResolver
2025-05-20T14:57:42.011308265Z 2025-05-20T14:57:42.010Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Detected FixedThemeResolver
2025-05-20T14:57:42.110258124Z 2025-05-20T14:57:42.109Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Detected org.springframework.web.servlet.view.DefaultRequestToViewNameTranslator@475ca2c6
2025-05-20T14:57:42.110807288Z 2025-05-20T14:57:42.110Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Detected org.springframework.web.servlet.support.SessionFlashMapManager@17765082
2025-05-20T14:57:42.111418274Z 2025-05-20T14:57:42.111Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : enableLoggingRequestDetails='false': request parameters and headers will be masked to prevent unsafe logging of potentially sensitive data
2025-05-20T14:57:42.112882312Z 2025-05-20T14:57:42.111Z  INFO 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Completed initialization in 102 ms
2025-05-20T14:57:48.378288487Z ==> Your service is live 🎉
2025-05-20T14:58:38.910405994Z 2025-05-20T14:58:38.909Z  INFO 1 --- [studio] [MessageBroker-1] o.s.w.s.c.WebSocketMessageBrokerStats    : WebSocketSession[0 current WS(0)-HttpStream(0)-HttpPoll(0), 0 total, 0 closed abnormally (0 connect failure, 0 send limit, 0 transport error)], stompSubProtocol[processed CONNECT(0)-CONNECTED(0)-DISCONNECT(0)], stompBrokerRelay[null], inboundChannel[pool size = 0, active threads = 0, queued tasks = 0, completed tasks = 0], outboundChannel[pool size = 0, active threads = 0, queued tasks = 0, completed tasks = 0], sockJsScheduler[pool size = 1, active threads = 1, queued tasks = 0, completed tasks = 0]
2025-05-20T15:02:04.305007684Z 2025-05-20T15:02:04.304Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.web.servlet.DispatcherServlet        : POST "/api/users/login", parameters={}
2025-05-20T15:02:04.308030442Z 2025-05-20T15:02:04.307Z DEBUG 1 --- [studio] [io-10000-exec-7] s.w.s.m.m.a.RequestMappingHandlerMapping : Mapped to io.metaverse.fashion.studio.controller.UserController#login(Map)
2025-05-20T15:02:04.915535044Z 2025-05-20T15:02:04.915Z DEBUG 1 --- [studio] [io-10000-exec-7] m.m.a.RequestResponseBodyMethodProcessor : Read "application/json;charset=UTF-8" to [{username=admin, password=password}]
2025-05-20T15:02:06.419142741Z Hibernate: 
2025-05-20T15:02:06.419163702Z     select
2025-05-20T15:02:06.419168362Z         u1_0.id,
2025-05-20T15:02:06.419173082Z         u1_0.email,
2025-05-20T15:02:06.419177212Z         u1_0.password,
2025-05-20T15:02:06.419181012Z         u1_0.username 
2025-05-20T15:02:06.419185052Z     from
2025-05-20T15:02:06.419190302Z         users u1_0 
2025-05-20T15:02:06.419194362Z     where
2025-05-20T15:02:06.419198293Z         u1_0.username=?
2025-05-20T15:02:07.211635576Z 2025-05-20T15:02:07.211Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Using 'application/json', given [*/*] and supported [application/json, application/*+json, application/yaml]
2025-05-20T15:02:07.213031162Z 2025-05-20T15:02:07.212Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Writing [{message=Login successful, user=admin}]
2025-05-20T15:02:07.413179201Z 2025-05-20T15:02:07.411Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.web.servlet.DispatcherServlet        : Completed 200 OK
2025-05-20T15:02:22.698223646Z 2025-05-20T15:02:22.697Z DEBUG 1 --- [studio] [io-10000-exec-2] o.s.web.servlet.DispatcherServlet        : GET "/api/designs/all", parameters={}
2025-05-20T15:02:22.698723119Z 2025-05-20T15:02:22.698Z DEBUG 1 --- [studio] [io-10000-exec-2] s.w.s.m.m.a.RequestMappingHandlerMapping : Mapped to io.metaverse.fashion.studio.controller.DesignController#getAllDesigns()
2025-05-20T15:02:22.904787703Z Hibernate: 
2025-05-20T15:02:22.904812223Z     select
2025-05-20T15:02:22.904817804Z         cd1_0.id,
2025-05-20T15:02:22.904822404Z         cd1_0.gender,
2025-05-20T15:02:22.904826734Z         cd1_0.image_url,
2025-05-20T15:02:22.904831224Z         cd1_0.prompt,
2025-05-20T15:02:22.904835614Z         cd1_0.style 
2025-05-20T15:02:22.904839704Z     from
2025-05-20T15:02:22.904845114Z         clothing_designs cd1_0
2025-05-20T15:02:23.105404564Z 2025-05-20T15:02:23.105Z DEBUG 1 --- [studio] [io-10000-exec-2] m.m.a.RequestResponseBodyMethodProcessor : Using 'application/json', given [application/json, text/plain, */*] and supported [application/json, application/*+json, application/yaml]
2025-05-20T15:02:23.105963829Z 2025-05-20T15:02:23.105Z DEBUG 1 --- [studio] [io-10000-exec-2] m.m.a.RequestResponseBodyMethodProcessor : Writing [[io.metaverse.fashion.studio.entity.ClothingDesign@55fd2ce3, io.metaverse.fashion.studio.entity.Clot (truncated)...]
2025-05-20T15:02:23.404703399Z 2025-05-20T15:02:23.404Z DEBUG 1 --- [studio] [io-10000-exec-2] o.s.web.servlet.DispatcherServlet        : Completed 200 OK
2025-05-20T15:02:52.97327564Z ==> Detected service running on port 10000
2025-05-20T15:02:53.070027757Z ==> Docs on specifying a port: https://render.com/docs/web-services#port-binding
2025-05-20T15:03:35.510138125Z 2025-05-20T15:03:35.509Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : POST "/api/virtual-tryon/try-on", parameters={multipart}
2025-05-20T15:03:36.307570781Z 2025-05-20T15:03:36.306Z DEBUG 1 --- [studio] [io-10000-exec-1] s.w.s.m.m.a.RequestMappingHandlerMapping : Mapped to io.metaverse.fashion.studio.controller.VirtualTryOnController#tryOnClothing(MultipartFile, MultipartFile)
2025-05-20T15:03:36.513605195Z 2025-05-20T15:03:36.513Z  INFO 1 --- [studio] [io-10000-exec-1] i.m.f.s.service.VirtualTryOnService      : Starting processImages method
2025-05-20T15:03:36.645553846Z 2025-05-20T15:03:36.644Z  INFO 1 --- [studio] [io-10000-exec-1] i.m.f.s.service.VirtualTryOnService      : File saved: /app/src/main/resources/static/vton/user_532d60ad-053e-49e4-b598-3eff3a4a207a_yg.jpg
2025-05-20T15:03:36.687773527Z 2025-05-20T15:03:36.687Z  INFO 1 --- [studio] [io-10000-exec-1] i.m.f.s.service.VirtualTryOnService      : File saved: /app/src/main/resources/static/vton/cloth_6b0e2ed4-22eb-4103-9cf8-ae339144d851_01887455500-e1-removebg-preview.png
2025-05-20T15:03:36.688028803Z 2025-05-20T15:03:36.687Z  INFO 1 --- [studio] [io-10000-exec-1] i.m.f.s.service.VirtualTryOnService      : User image saved at: /app/src/main/resources/static/vton/user_532d60ad-053e-49e4-b598-3eff3a4a207a_yg.jpg
2025-05-20T15:03:36.689156093Z 2025-05-20T15:03:36.688Z  INFO 1 --- [studio] [io-10000-exec-1] i.m.f.s.service.VirtualTryOnService      : Cloth image saved at: /app/src/main/resources/static/vton/cloth_6b0e2ed4-22eb-4103-9cf8-ae339144d851_01887455500-e1-removebg-preview.png
2025-05-20T15:03:36.94059615Z 2025-05-20T15:03:36.940Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Using 'application/json', given [application/json, text/plain, */*] and supported [text/plain, */*, application/json, application/*+json, application/yaml]
2025-05-20T15:03:36.954296438Z 2025-05-20T15:03:36.950Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Writing ["Error processing request: Cannot run program "python": error=2, No such file or directory"]
2025-05-20T15:03:36.96089488Z 2025-05-20T15:03:36.958Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Completed 500 INTERNAL_SERVER_ERROR
2025-05-20T15:04:48.517140402Z 2025-05-20T15:04:48.516Z DEBUG 1 --- [studio] [o-10000-exec-10] o.s.web.servlet.DispatcherServlet        : GET "/api/outfit/suggest?occasion=Wedding&gender=male&season=spring", parameters={masked}
2025-05-20T15:04:48.517565073Z 2025-05-20T15:04:48.517Z DEBUG 1 --- [studio] [o-10000-exec-10] s.w.s.m.m.a.RequestMappingHandlerMapping : Mapped to io.metaverse.fashion.studio.controller.OutfitSuggestionController#suggestOutfit(String, String, String)
2025-05-20T15:04:48.605377524Z 2025-05-20T15:04:48.519Z  INFO 1 --- [studio] [o-10000-exec-10] i.m.f.s.service.OutfitSuggestionService  : Executing enhanced Python script for occasion: Wedding, gender: male, season: spring
2025-05-20T15:04:48.805774511Z 2025-05-20T15:04:48.606Z ERROR 1 --- [studio] [o-10000-exec-10] i.m.f.s.service.OutfitSuggestionService  : Error executing Python script: Cannot run program "python": error=2, No such file or directory
2025-05-20T15:04:48.805797871Z 
2025-05-20T15:04:48.805803151Z java.io.IOException: Cannot run program "python": error=2, No such file or directory
2025-05-20T15:04:48.805807771Z 	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1143) ~[na:na]
2025-05-20T15:04:48.805812732Z 	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1073) ~[na:na]
2025-05-20T15:04:48.805819192Z 	at io.metaverse.fashion.studio.service.OutfitSuggestionService.getOutfitSuggestion(OutfitSuggestionService.java:44) ~[!/:0.0.1-SNAPSHOT]
2025-05-20T15:04:48.805823782Z 	at io.metaverse.fashion.studio.service.OutfitSuggestionService.callGetOutfitSuggestion(OutfitSuggestionService.java:27) ~[!/:0.0.1-SNAPSHOT]
2025-05-20T15:04:48.805842032Z 	at io.metaverse.fashion.studio.controller.OutfitSuggestionController.suggestOutfit(OutfitSuggestionController.java:27) ~[!/:0.0.1-SNAPSHOT]
2025-05-20T15:04:48.805845212Z 	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
2025-05-20T15:04:48.805849503Z 	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[na:na]
2025-05-20T15:04:48.805853593Z 	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
2025-05-20T15:04:48.805856183Z 	at java.base/java.lang.reflect.Method.invoke(Method.java:568) ~[na:na]
2025-05-20T15:04:48.805858873Z 	at org.springframework.web.method.support.InvocableHandlerMethod.doInvoke(InvocableHandlerMethod.java:258) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805863213Z 	at org.springframework.web.method.support.InvocableHandlerMethod.invokeForRequest(InvocableHandlerMethod.java:191) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805867703Z 	at org.springframework.web.servlet.mvc.method.annotation.ServletInvocableHandlerMethod.invokeAndHandle(ServletInvocableHandlerMethod.java:118) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805870313Z 	at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.invokeHandlerMethod(RequestMappingHandlerAdapter.java:986) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805874243Z 	at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.handleInternal(RequestMappingHandlerAdapter.java:891) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805877163Z 	at org.springframework.web.servlet.mvc.method.AbstractHandlerMethodAdapter.handle(AbstractHandlerMethodAdapter.java:87) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805879723Z 	at org.springframework.web.servlet.DispatcherServlet.doDispatch(DispatcherServlet.java:1089) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805882313Z 	at org.springframework.web.servlet.DispatcherServlet.doService(DispatcherServlet.java:979) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805884993Z 	at org.springframework.web.servlet.FrameworkServlet.processRequest(FrameworkServlet.java:1014) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805887733Z 	at org.springframework.web.servlet.FrameworkServlet.doGet(FrameworkServlet.java:903) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805890384Z 	at jakarta.servlet.http.HttpServlet.service(HttpServlet.java:564) ~[tomcat-embed-core-10.1.39.jar!/:6.0.0]
2025-05-20T15:04:48.805893174Z 	at org.springframework.web.servlet.FrameworkServlet.service(FrameworkServlet.java:885) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805895874Z 	at jakarta.servlet.http.HttpServlet.service(HttpServlet.java:658) ~[tomcat-embed-core-10.1.39.jar!/:6.0.0]
2025-05-20T15:04:48.805898294Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:195) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.805901384Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.805904114Z 	at org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:51) ~[tomcat-embed-websocket-10.1.39.jar!/:na]
2025-05-20T15:04:48.805906864Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.805909424Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.805912004Z 	at org.springframework.web.filter.CompositeFilter$VirtualFilterChain.doFilter(CompositeFilter.java:108) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.805920474Z 	at org.springframework.security.web.FilterChainProxy.lambda$doFilterInternal$3(FilterChainProxy.java:231) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805927045Z 	at org.springframework.security.web.ObservationFilterChainDecorator$FilterObservation$SimpleFilterObservation.lambda$wrap$1(ObservationFilterChainDecorator.java:479) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805931515Z 	at org.springframework.security.web.ObservationFilterChainDecorator$AroundFilterObservation$SimpleAroundFilterObservation.lambda$wrap$1(ObservationFilterChainDecorator.java:340) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805934605Z 	at org.springframework.security.web.ObservationFilterChainDecorator.lambda$wrapSecured$0(ObservationFilterChainDecorator.java:82) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805937465Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:128) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805940405Z 	at org.springframework.security.web.access.intercept.AuthorizationFilter.doFilter(AuthorizationFilter.java:101) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805943285Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805946065Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805949015Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805951995Z 	at org.springframework.security.web.access.ExceptionTranslationFilter.doFilter(ExceptionTranslationFilter.java:126) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805954725Z 	at org.springframework.security.web.access.ExceptionTranslationFilter.doFilter(ExceptionTranslationFilter.java:120) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805957595Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805960535Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805963366Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805966226Z 	at org.springframework.security.web.authentication.AnonymousAuthenticationFilter.doFilter(AnonymousAuthenticationFilter.java:100) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805969316Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805972296Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805975286Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805978016Z 	at org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter.doFilter(SecurityContextHolderAwareRequestFilter.java:179) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805986396Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805989156Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805991886Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805994316Z 	at org.springframework.security.web.savedrequest.RequestCacheAwareFilter.doFilter(RequestCacheAwareFilter.java:63) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.805999187Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806001987Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806004677Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806007597Z 	at org.springframework.security.web.authentication.logout.LogoutFilter.doFilter(LogoutFilter.java:107) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806010347Z 	at org.springframework.security.web.authentication.logout.LogoutFilter.doFilter(LogoutFilter.java:93) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806013017Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806015487Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806018327Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806021127Z 	at org.springframework.web.filter.CorsFilter.doFilterInternal(CorsFilter.java:91) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806023867Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806026497Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806029097Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806031777Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806034668Z 	at org.springframework.security.web.header.HeaderWriterFilter.doHeadersAfter(HeaderWriterFilter.java:90) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806037588Z 	at org.springframework.security.web.header.HeaderWriterFilter.doFilterInternal(HeaderWriterFilter.java:75) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806045008Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806047488Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806051678Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806054328Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806056738Z 	at org.springframework.security.web.context.SecurityContextHolderFilter.doFilter(SecurityContextHolderFilter.java:82) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806059328Z 	at org.springframework.security.web.context.SecurityContextHolderFilter.doFilter(SecurityContextHolderFilter.java:69) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806061688Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806063938Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806066258Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806070688Z 	at org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter.doFilterInternal(WebAsyncManagerIntegrationFilter.java:62) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806073229Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806095629Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806102199Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806104809Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806107489Z 	at org.springframework.security.web.session.DisableEncodeUrlFilter.doFilterInternal(DisableEncodeUrlFilter.java:42) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806109939Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806112439Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806115079Z 	at org.springframework.security.web.ObservationFilterChainDecorator$AroundFilterObservation$SimpleAroundFilterObservation.lambda$wrap$0(ObservationFilterChainDecorator.java:323) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.806117739Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:224) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.80612012Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.80612759Z 	at org.springframework.security.web.FilterChainProxy.doFilterInternal(FilterChainProxy.java:233) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.8061304Z 	at org.springframework.security.web.FilterChainProxy.doFilter(FilterChainProxy.java:191) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.80613295Z 	at org.springframework.web.filter.CompositeFilter$VirtualFilterChain.doFilter(CompositeFilter.java:113) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.80613603Z 	at org.springframework.web.servlet.handler.HandlerMappingIntrospector.lambda$createCacheFilter$3(HandlerMappingIntrospector.java:243) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.80613886Z 	at org.springframework.web.filter.CompositeFilter$VirtualFilterChain.doFilter(CompositeFilter.java:113) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.80614173Z 	at org.springframework.web.filter.CompositeFilter.doFilter(CompositeFilter.java:74) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.80614433Z 	at org.springframework.security.config.annotation.web.configuration.WebMvcSecurityConfiguration$CompositeFilterChainProxy.doFilter(WebMvcSecurityConfiguration.java:238) ~[spring-security-config-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.80614704Z 	at org.springframework.web.filter.DelegatingFilterProxy.invokeDelegate(DelegatingFilterProxy.java:362) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.8061498Z 	at org.springframework.web.filter.DelegatingFilterProxy.doFilter(DelegatingFilterProxy.java:278) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.80615294Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806155551Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806157931Z 	at org.springframework.web.filter.RequestContextFilter.doFilterInternal(RequestContextFilter.java:100) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806160751Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806163601Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806166151Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806171911Z 	at org.springframework.web.filter.FormContentFilter.doFilterInternal(FormContentFilter.java:93) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806174861Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806177501Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806180151Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806182821Z 	at org.springframework.web.filter.ServerHttpObservationFilter.doFilterInternal(ServerHttpObservationFilter.java:114) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806185791Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806188832Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806191501Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806199442Z 	at org.springframework.web.filter.CharacterEncodingFilter.doFilterInternal(CharacterEncodingFilter.java:201) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806202152Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.806204722Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806207492Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806210122Z 	at org.apache.catalina.core.StandardWrapperValve.invoke(StandardWrapperValve.java:167) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806212922Z 	at org.apache.catalina.core.StandardContextValve.invoke(StandardContextValve.java:90) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806215472Z 	at org.apache.catalina.authenticator.AuthenticatorBase.invoke(AuthenticatorBase.java:483) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806218072Z 	at org.apache.catalina.core.StandardHostValve.invoke(StandardHostValve.java:115) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806220992Z 	at org.apache.catalina.valves.ErrorReportValve.invoke(ErrorReportValve.java:93) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806223762Z 	at org.apache.catalina.core.StandardEngineValve.invoke(StandardEngineValve.java:74) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806226273Z 	at org.apache.catalina.valves.RemoteIpValve.invoke(RemoteIpValve.java:731) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806228742Z 	at org.apache.catalina.connector.CoyoteAdapter.service(CoyoteAdapter.java:344) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806231022Z 	at org.apache.coyote.http11.Http11Processor.service(Http11Processor.java:397) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806233483Z 	at org.apache.coyote.AbstractProcessorLight.process(AbstractProcessorLight.java:63) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806235913Z 	at org.apache.coyote.AbstractProtocol$ConnectionHandler.process(AbstractProtocol.java:905) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806238243Z 	at org.apache.tomcat.util.net.NioEndpoint$SocketProcessor.doRun(NioEndpoint.java:1743) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806240553Z 	at org.apache.tomcat.util.net.SocketProcessorBase.run(SocketProcessorBase.java:52) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806242983Z 	at org.apache.tomcat.util.threads.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1190) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806245523Z 	at org.apache.tomcat.util.threads.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:659) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806247833Z 	at org.apache.tomcat.util.threads.TaskThread$WrappingRunnable.run(TaskThread.java:63) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.806250983Z 	at java.base/java.lang.Thread.run(Thread.java:833) ~[na:na]
2025-05-20T15:04:48.806253743Z Caused by: java.io.IOException: error=2, No such file or directory
2025-05-20T15:04:48.806256223Z 	at java.base/java.lang.ProcessImpl.forkAndExec(Native Method) ~[na:na]
2025-05-20T15:04:48.806258533Z 	at java.base/java.lang.ProcessImpl.<init>(ProcessImpl.java:314) ~[na:na]
2025-05-20T15:04:48.806260863Z 	at java.base/java.lang.ProcessImpl.start(ProcessImpl.java:244) ~[na:na]
2025-05-20T15:04:48.806263353Z 	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1110) ~[na:na]
2025-05-20T15:04:48.806270503Z 	... 129 common frames omitted
2025-05-20T15:04:48.806272804Z 
2025-05-20T15:04:48.810188426Z 2025-05-20T15:04:48.808Z DEBUG 1 --- [studio] [o-10000-exec-10] o.s.web.servlet.DispatcherServlet        : Failed to complete request: java.lang.RuntimeException: Python script execution failed
2025-05-20T15:04:48.811829849Z 2025-05-20T15:04:48.810Z ERROR 1 --- [studio] [o-10000-exec-10] o.a.c.c.C.[.[.[/].[dispatcherServlet]    : Servlet.service() for servlet [dispatcherServlet] in context with path [] threw exception [Request processing failed: java.lang.RuntimeException: Python script execution failed] with root cause
2025-05-20T15:04:48.811844999Z 
2025-05-20T15:04:48.811849459Z java.io.IOException: error=2, No such file or directory
2025-05-20T15:04:48.811853229Z 	at java.base/java.lang.ProcessImpl.forkAndExec(Native Method) ~[na:na]
2025-05-20T15:04:48.811856139Z 	at java.base/java.lang.ProcessImpl.<init>(ProcessImpl.java:314) ~[na:na]
2025-05-20T15:04:48.811858929Z 	at java.base/java.lang.ProcessImpl.start(ProcessImpl.java:244) ~[na:na]
2025-05-20T15:04:48.811861709Z 	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1110) ~[na:na]
2025-05-20T15:04:48.8118644Z 	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1073) ~[na:na]
2025-05-20T15:04:48.81187076Z 	at io.metaverse.fashion.studio.service.OutfitSuggestionService.getOutfitSuggestion(OutfitSuggestionService.java:44) ~[!/:0.0.1-SNAPSHOT]
2025-05-20T15:04:48.81187414Z 	at io.metaverse.fashion.studio.service.OutfitSuggestionService.callGetOutfitSuggestion(OutfitSuggestionService.java:27) ~[!/:0.0.1-SNAPSHOT]
2025-05-20T15:04:48.81187689Z 	at io.metaverse.fashion.studio.controller.OutfitSuggestionController.suggestOutfit(OutfitSuggestionController.java:27) ~[!/:0.0.1-SNAPSHOT]
2025-05-20T15:04:48.81188045Z 	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
2025-05-20T15:04:48.81188404Z 	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[na:na]
2025-05-20T15:04:48.81188725Z 	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
2025-05-20T15:04:48.81189024Z 	at java.base/java.lang.reflect.Method.invoke(Method.java:568) ~[na:na]
2025-05-20T15:04:48.81189288Z 	at org.springframework.web.method.support.InvocableHandlerMethod.doInvoke(InvocableHandlerMethod.java:258) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.81189669Z 	at org.springframework.web.method.support.InvocableHandlerMethod.invokeForRequest(InvocableHandlerMethod.java:191) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811899821Z 	at org.springframework.web.servlet.mvc.method.annotation.ServletInvocableHandlerMethod.invokeAndHandle(ServletInvocableHandlerMethod.java:118) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.81190157Z 	at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.invokeHandlerMethod(RequestMappingHandlerAdapter.java:986) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811904011Z 	at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.handleInternal(RequestMappingHandlerAdapter.java:891) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811905761Z 	at org.springframework.web.servlet.mvc.method.AbstractHandlerMethodAdapter.handle(AbstractHandlerMethodAdapter.java:87) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811907531Z 	at org.springframework.web.servlet.DispatcherServlet.doDispatch(DispatcherServlet.java:1089) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811909421Z 	at org.springframework.web.servlet.DispatcherServlet.doService(DispatcherServlet.java:979) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811920991Z 	at org.springframework.web.servlet.FrameworkServlet.processRequest(FrameworkServlet.java:1014) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811922901Z 	at org.springframework.web.servlet.FrameworkServlet.doGet(FrameworkServlet.java:903) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811924681Z 	at jakarta.servlet.http.HttpServlet.service(HttpServlet.java:564) ~[tomcat-embed-core-10.1.39.jar!/:6.0.0]
2025-05-20T15:04:48.811926701Z 	at org.springframework.web.servlet.FrameworkServlet.service(FrameworkServlet.java:885) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811928411Z 	at jakarta.servlet.http.HttpServlet.service(HttpServlet.java:658) ~[tomcat-embed-core-10.1.39.jar!/:6.0.0]
2025-05-20T15:04:48.811930401Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:195) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.811932191Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.811933971Z 	at org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:51) ~[tomcat-embed-websocket-10.1.39.jar!/:na]
2025-05-20T15:04:48.811935651Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.811937331Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.811947692Z 	at org.springframework.web.filter.CompositeFilter$VirtualFilterChain.doFilter(CompositeFilter.java:108) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.811951112Z 	at org.springframework.security.web.FilterChainProxy.lambda$doFilterInternal$3(FilterChainProxy.java:231) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811954652Z 	at org.springframework.security.web.ObservationFilterChainDecorator$FilterObservation$SimpleFilterObservation.lambda$wrap$1(ObservationFilterChainDecorator.java:479) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811958262Z 	at org.springframework.security.web.ObservationFilterChainDecorator$AroundFilterObservation$SimpleAroundFilterObservation.lambda$wrap$1(ObservationFilterChainDecorator.java:340) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811961582Z 	at org.springframework.security.web.ObservationFilterChainDecorator.lambda$wrapSecured$0(ObservationFilterChainDecorator.java:82) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811964882Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:128) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811967662Z 	at org.springframework.security.web.access.intercept.AuthorizationFilter.doFilter(AuthorizationFilter.java:101) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811970342Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811973232Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811976052Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811978512Z 	at org.springframework.security.web.access.ExceptionTranslationFilter.doFilter(ExceptionTranslationFilter.java:126) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811980743Z 	at org.springframework.security.web.access.ExceptionTranslationFilter.doFilter(ExceptionTranslationFilter.java:120) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811988343Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811990803Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811993133Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811995633Z 	at org.springframework.security.web.authentication.AnonymousAuthenticationFilter.doFilter(AnonymousAuthenticationFilter.java:100) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.811998113Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812000893Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812003893Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812007103Z 	at org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter.doFilter(SecurityContextHolderAwareRequestFilter.java:179) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812009013Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812010764Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812012513Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812021994Z 	at org.springframework.security.web.savedrequest.RequestCacheAwareFilter.doFilter(RequestCacheAwareFilter.java:63) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812027174Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812030264Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812033424Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812036284Z 	at org.springframework.security.web.authentication.logout.LogoutFilter.doFilter(LogoutFilter.java:107) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812039044Z 	at org.springframework.security.web.authentication.logout.LogoutFilter.doFilter(LogoutFilter.java:93) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812041634Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812044104Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812051905Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812054765Z 	at org.springframework.web.filter.CorsFilter.doFilterInternal(CorsFilter.java:91) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812057405Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812060195Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812062975Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812065645Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812068445Z 	at org.springframework.security.web.header.HeaderWriterFilter.doHeadersAfter(HeaderWriterFilter.java:90) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812071175Z 	at org.springframework.security.web.header.HeaderWriterFilter.doFilterInternal(HeaderWriterFilter.java:75) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812073795Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812130027Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812137427Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812140287Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812143157Z 	at org.springframework.security.web.context.SecurityContextHolderFilter.doFilter(SecurityContextHolderFilter.java:82) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812148327Z 	at org.springframework.security.web.context.SecurityContextHolderFilter.doFilter(SecurityContextHolderFilter.java:69) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812151207Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812154267Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812166148Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812169148Z 	at org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter.doFilterInternal(WebAsyncManagerIntegrationFilter.java:62) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812171888Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812174678Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812182928Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:227) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812185708Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812188478Z 	at org.springframework.security.web.session.DisableEncodeUrlFilter.doFilterInternal(DisableEncodeUrlFilter.java:42) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812191318Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812194258Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.wrapFilter(ObservationFilterChainDecorator.java:240) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812197268Z 	at org.springframework.security.web.ObservationFilterChainDecorator$AroundFilterObservation$SimpleAroundFilterObservation.lambda$wrap$0(ObservationFilterChainDecorator.java:323) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812200118Z 	at org.springframework.security.web.ObservationFilterChainDecorator$ObservationFilter.doFilter(ObservationFilterChainDecorator.java:224) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812202818Z 	at org.springframework.security.web.ObservationFilterChainDecorator$VirtualFilterChain.doFilter(ObservationFilterChainDecorator.java:137) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812205869Z 	at org.springframework.security.web.FilterChainProxy.doFilterInternal(FilterChainProxy.java:233) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812208489Z 	at org.springframework.security.web.FilterChainProxy.doFilter(FilterChainProxy.java:191) ~[spring-security-web-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812210989Z 	at org.springframework.web.filter.CompositeFilter$VirtualFilterChain.doFilter(CompositeFilter.java:113) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812213599Z 	at org.springframework.web.servlet.handler.HandlerMappingIntrospector.lambda$createCacheFilter$3(HandlerMappingIntrospector.java:243) ~[spring-webmvc-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812216559Z 	at org.springframework.web.filter.CompositeFilter$VirtualFilterChain.doFilter(CompositeFilter.java:113) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812219019Z 	at org.springframework.web.filter.CompositeFilter.doFilter(CompositeFilter.java:74) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812221709Z 	at org.springframework.security.config.annotation.web.configuration.WebMvcSecurityConfiguration$CompositeFilterChainProxy.doFilter(WebMvcSecurityConfiguration.java:238) ~[spring-security-config-6.4.4.jar!/:6.4.4]
2025-05-20T15:04:48.812224409Z 	at org.springframework.web.filter.DelegatingFilterProxy.invokeDelegate(DelegatingFilterProxy.java:362) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812229679Z 	at org.springframework.web.filter.DelegatingFilterProxy.doFilter(DelegatingFilterProxy.java:278) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812232599Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812235389Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812238039Z 	at org.springframework.web.filter.RequestContextFilter.doFilterInternal(RequestContextFilter.java:100) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.81224083Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.81224844Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.81226367Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.81226703Z 	at org.springframework.web.filter.FormContentFilter.doFilterInternal(FormContentFilter.java:93) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.81227003Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.81227285Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.81227553Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.81227844Z 	at org.springframework.web.filter.ServerHttpObservationFilter.doFilterInternal(ServerHttpObservationFilter.java:114) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812281091Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812283931Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812286801Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812289431Z 	at org.springframework.web.filter.CharacterEncodingFilter.doFilterInternal(CharacterEncodingFilter.java:201) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812292181Z 	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116) ~[spring-web-6.2.5.jar!/:6.2.5]
2025-05-20T15:04:48.812294681Z 	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:164) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812297561Z 	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:140) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812300281Z 	at org.apache.catalina.core.StandardWrapperValve.invoke(StandardWrapperValve.java:167) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812303041Z 	at org.apache.catalina.core.StandardContextValve.invoke(StandardContextValve.java:90) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812306131Z 	at org.apache.catalina.authenticator.AuthenticatorBase.invoke(AuthenticatorBase.java:483) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812309011Z 	at org.apache.catalina.core.StandardHostValve.invoke(StandardHostValve.java:115) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812311911Z 	at org.apache.catalina.valves.ErrorReportValve.invoke(ErrorReportValve.java:93) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812314751Z 	at org.apache.catalina.core.StandardEngineValve.invoke(StandardEngineValve.java:74) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812317621Z 	at org.apache.catalina.valves.RemoteIpValve.invoke(RemoteIpValve.java:731) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812320492Z 	at org.apache.catalina.connector.CoyoteAdapter.service(CoyoteAdapter.java:344) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812323312Z 	at org.apache.coyote.http11.Http11Processor.service(Http11Processor.java:397) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812326012Z 	at org.apache.coyote.AbstractProcessorLight.process(AbstractProcessorLight.java:63) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812333342Z 	at org.apache.coyote.AbstractProtocol$ConnectionHandler.process(AbstractProtocol.java:905) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812335892Z 	at org.apache.tomcat.util.net.NioEndpoint$SocketProcessor.doRun(NioEndpoint.java:1743) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812340662Z 	at org.apache.tomcat.util.net.SocketProcessorBase.run(SocketProcessorBase.java:52) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812343542Z 	at org.apache.tomcat.util.threads.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1190) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812346192Z 	at org.apache.tomcat.util.threads.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:659) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812349062Z 	at org.apache.tomcat.util.threads.TaskThread$WrappingRunnable.run(TaskThread.java:63) ~[tomcat-embed-core-10.1.39.jar!/:na]
2025-05-20T15:04:48.812351832Z 	at java.base/java.lang.Thread.run(Thread.java:833) ~[na:na]
2025-05-20T15:04:48.812354262Z 
2025-05-20T15:05:27.607244902Z 2025-05-20T15:05:27.605Z DEBUG 1 --- [studio] [io-10000-exec-8] o.s.web.servlet.DispatcherServlet        : GET "/virtual-try-on-websocket/info?t=1747753526868", parameters={masked}
2025-05-20T15:05:27.607329795Z 2025-05-20T15:05:27.606Z DEBUG 1 --- [studio] [io-10000-exec-8] o.s.w.s.s.s.WebSocketHandlerMapping      : Mapped to org.springframework.web.socket.sockjs.support.SockJsHttpRequestHandler@52418721
2025-05-20T15:05:27.610129848Z 2025-05-20T15:05:27.608Z DEBUG 1 --- [studio] [io-10000-exec-8] o.s.w.s.s.t.h.DefaultSockJsService       : Processing transport request: GET https://fashion-studio-ai-zbt4.onrender.com/virtual-try-on-websocket/info?t=1747753526868
2025-05-20T15:05:27.611139634Z 2025-05-20T15:05:27.610Z DEBUG 1 --- [studio] [io-10000-exec-8] o.s.web.servlet.DispatcherServlet        : Completed 200 OK
2025-05-20T15:05:28.369146036Z 2025-05-20T15:05:28.368Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : GET "/virtual-try-on-websocket/967/2parkmj1/websocket", parameters={}
2025-05-20T15:05:28.369953477Z 2025-05-20T15:05:28.369Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.w.s.s.s.WebSocketHandlerMapping      : Mapped to org.springframework.web.socket.sockjs.support.SockJsHttpRequestHandler@52418721
2025-05-20T15:05:28.372699519Z 2025-05-20T15:05:28.372Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.w.s.s.t.h.DefaultSockJsService       : Processing transport request: GET https://fashion-studio-ai-zbt4.onrender.com/virtual-try-on-websocket/967/2parkmj1/websocket
2025-05-20T15:05:28.715281284Z 2025-05-20T15:05:28.714Z DEBUG 1 --- [studio] [io-10000-exec-1] o.s.web.servlet.DispatcherServlet        : Completed 101 SWITCHING_PROTOCOLS
2025-05-20T15:05:28.917997642Z 2025-05-20T15:05:28.915Z DEBUG 1 --- [studio] [io-10000-exec-1] s.w.s.h.LoggingWebSocketHandlerDecorator : New WebSocketServerSockJsSession[id=2parkmj1]
2025-05-20T15:05:29.411347251Z 2025-05-20T15:05:29.407Z DEBUG 1 --- [studio] [nboundChannel-2] org.springframework.web.SimpLogging      : Processing CONNECT session=2parkmj1
2025-05-20T15:05:29.764537933Z 2025-05-20T15:05:29.763Z DEBUG 1 --- [studio] [nboundChannel-2] org.springframework.web.SimpLogging      : Processing SUBSCRIBE /topic/video-feed id=sub-0 session=2parkmj1
2025-05-20T15:05:42.185800046Z 2025-05-20T15:05:42.185Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.web.servlet.DispatcherServlet        : POST "/api/virtual-try-on/upload-cloth", parameters={multipart}
2025-05-20T15:05:42.776543956Z 2025-05-20T15:05:42.776Z DEBUG 1 --- [studio] [io-10000-exec-7] s.w.s.m.m.a.RequestMappingHandlerMapping : Mapped to io.metaverse.fashion.studio.controller.CamVirtualTryOnController#uploadClothImage(MultipartFile)
2025-05-20T15:05:42.806125177Z 2025-05-20T15:05:42.805Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Using 'text/plain', given [*/*] and supported [text/plain, */*, application/json, application/*+json, application/yaml]
2025-05-20T15:05:42.806433565Z 2025-05-20T15:05:42.806Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Writing ["Error processing image: Cannot run program "python": error=2, No such file or directory"]
2025-05-20T15:05:42.90439624Z 2025-05-20T15:05:42.808Z DEBUG 1 --- [studio] [io-10000-exec-7] o.s.web.servlet.DispatcherServlet        : Completed 400 BAD_REQUEST
2025-05-20T15:06:11.477267263Z 2025-05-20T15:06:11.475Z DEBUG 1 --- [studio] [io-10000-exec-5] s.w.s.h.LoggingWebSocketHandlerDecorator : WebSocketServerSockJsSession[id=2parkmj1] closed with CloseStatus[code=1000, reason=null]
2025-05-20T15:06:11.477294813Z 2025-05-20T15:06:11.475Z DEBUG 1 --- [studio] [io-10000-exec-5] o.s.w.s.m.SubProtocolWebSocketHandler    : Clearing session 2parkmj1
2025-05-20T15:06:11.477989211Z 2025-05-20T15:06:11.477Z DEBUG 1 --- [studio] [nboundChannel-1] org.springframework.web.SimpLogging      : Processing DISCONNECT session=2parkmj1
2025-05-20T15:06:11.479383608Z 2025-05-20T15:06:11.479Z DEBUG 1 --- [studio] [tboundChannel-2] o.s.w.s.m.SubProtocolWebSocketHandler    : No session for GenericMessage [payload=byte[0], headers={simpMessageType=DISCONNECT_ACK, simpDisconnectMessage=GenericMessage [payload=byte[0], headers={simpMessageType=DISCONNECT, stompCommand=DISCONNECT, simpSessionAttributes={org.springframework.messaging.simp.SimpAttributes.COMPLETED=true}, simpSessionId=2parkmj1}], simpSessionId=2parkmj1}]
2025-05-20T15:06:18.40848819Z 2025-05-20T15:06:18.408Z DEBUG 1 --- [studio] [MessageBroker-1] o.s.w.s.s.t.h.DefaultSockJsService       : Closed 1 sessions: [2parkmj1]
