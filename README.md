2025-06-03T17:12:51.357+05:30 DEBUG 9060 --- [studio] [io-8080-exec-10] o.s.web.servlet.DispatcherServlet        : GET "/api/outfit/suggest?gender=male&season=all&occasion=formal", parameters={masked}
2025-06-03T17:12:51.359+05:30 DEBUG 9060 --- [studio] [io-8080-exec-10] s.w.s.m.m.a.RequestMappingHandlerMapping : Mapped to io.metaverse.fashion.studio.controller.OutfitSuggestionController#suggestOutfit(String, String, String)
2025-06-03T17:12:51.363+05:30  INFO 9060 --- [studio] [io-8080-exec-10] i.m.f.s.service.OutfitSuggestionService  : Executing enhanced Python script for occasion: formal, gender: male, season: all
2025-06-03T17:12:51.780+05:30 DEBUG 9060 --- [studio] [io-8080-exec-10] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Found 'Content-Type:application/json' in response
2025-06-03T17:12:51.781+05:30 DEBUG 9060 --- [studio] [io-8080-exec-10] o.s.w.s.m.m.a.HttpEntityMethodProcessor  : Writing ["{"status": "success", "outfitSuggestion": "", "alternatives": ["", ""], "gender": "male", "season":  (truncated)..."]
2025-06-03T17:12:51.783+05:30 DEBUG 9060 --- [studio] [io-8080-exec-10] o.s.web.servlet.DispatcherServlet        : Completed 200 OK
2025-06-03T17:12:54.161+05:30 DEBUG 9060 --- [studio] [ool housekeeper] com.zaxxer.hikari.pool.HikariPool        : StudioHikariPool - Before cleanup stats (total=2, active=0, idle=2, waiting=0)
2025-06-03T17:12:54.161+05:30 DEBUG 9060 --- [studio] [ool housekeeper] com.zaxxer.hikari.pool.HikariPool        : StudioHikariPool - After cleanup  stats (total=2, active=0, idle=2, waiting=0)
2025-06-03T17:12:54.162+05:30 DEBUG 9060 --- [studio] [ool housekeeper] com.zaxxer.hikari.pool.HikariPool        : StudioHikariPool - Fill pool skipped, pool has sufficient level or currently being filled.
