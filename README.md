2025-06-03T15:46:24.631+05:30 DEBUG 11148 --- [studio] [nio-8080-exec-2] o.s.web.servlet.DispatcherServlet        : GET "/api/outfit/suggest?gender=female&season=summer&occasion=traditional", parameters={masked}
2025-06-03T15:46:24.634+05:30 DEBUG 11148 --- [studio] [nio-8080-exec-2] s.w.s.m.m.a.RequestMappingHandlerMapping : Mapped to io.metaverse.fashion.studio.controller.OutfitSuggestionController#suggestOutfit(String, String, String)
2025-06-03T15:46:24.636+05:30  INFO 11148 --- [studio] [nio-8080-exec-2] i.m.f.s.service.OutfitSuggestionService  : Executing enhanced Python script for occasion: traditional, gender: female, season: summer
2025-06-03T15:46:25.014+05:30 DEBUG 11148 --- [studio] [nio-8080-exec-2] m.m.a.RequestResponseBodyMethodProcessor : Using 'application/json', given [application/json, text/plain, */*] and supported [text/plain, */*, application/json, application/*+json, application/yaml]
2025-06-03T15:46:25.015+05:30 DEBUG 11148 --- [studio] [nio-8080-exec-2] m.m.a.RequestResponseBodyMethodProcessor : Writing ["Main suggestion: red sari<EOL><EOL>Alternative options:<EOL>- red sari<EOL>- red sari<EOL>"]

this is backend log.

but in frontend we are getting failed to get sugesstion
