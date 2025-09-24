This notebook demonstrates end-to-end SQL analytics on the classic Chinook database using Python (pandas + SQLAlchemy) with a MySQL backend. It connects to MySQL, runs 35+ queries (joins, subqueries, window functions, rankings, aggregates), and saves results for autograding/inspection.


Query highlights (examples)

q3: All tracks released by Queen (via subquery on artist → albums → tracks). <br>
q6: Top 5 longest Queen tracks (ORDER BY Milliseconds DESC). <br>
q8: Human-readable track listing with DurationMinutes and FileSize (MB). <br>
q15: Customer names joined with their invoice totals. <br>
q17/q20: Invoice details (global vs. USA) for Queen purchases. <br>
q26: Total album duration (hours) and top 5 longest albums. <br>
q29: Genres with average track duration > 20 minutes. <br>
q34: Top-3 invoices per country using RANK() OVER (PARTITION BY ...). <br>
q35: Monthly sales with a 3-month moving average.<br>
