SELECT c.contest_id, c.hacker_id,
c.name,SUM(v.total_views),SUM(v.total_unique_views),SUM(s.total_submissions),
SUM(s.total_accepted_submissions) FROM CONTESTS c, College co, Challenge ch ,
View_Stats v, Submission_Stats s
WHERE c.contest_id = co.contest_id && co.college_id = ch.challenge_id ORDER BY
(c.contest_id)
