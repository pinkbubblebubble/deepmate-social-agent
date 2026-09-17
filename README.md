# Social Agent Quiz — GitHub Pages v3

Updated six-type classification:
- 破冰火花体 (icebreaker)
- 缘分雷达体 (radar)
- 关系侦探体 (detective)
- 关系记忆体 (keeper)
- 行动加速体 (secretary)
- 边界守护体 (guardian)

All questions now affect classification. Each selected option adds exactly 1 point to one type. If scores tie, the most recently selected tied type wins.

Supabase schema does not need changes for this update. Existing generic `answers` rows already store `question_id` and `option_id`, while `completions.result_type` is text and can store `detective`. The session writes `survey_version=v3_2026-09-16`.

Deploy with GitHub Pages: Settings → Pages → Deploy from a branch → main / root.

The quiz now has 10 questions (including cooperation, relationship maintenance and interest groups). The home screen count matches the question list, and each new question/result returns to the top on mobile.
