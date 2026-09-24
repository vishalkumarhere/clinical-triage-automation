# Clinical Referral & Infusion Order Triage Automation

An agent based automation pipeline, modeled on Epic Beacon style oncology infusion
and referral workflows, that ingests incoming orders, auto classifies priority,
flags missing prior authorization or scheduling conflicts, and drafts a structured
review summary before an order reaches a staff queue.

Built as a healthcare AI automation portfolio project. All order and workflow data
on the live demo is illustrative synthetic data modeled on publicly described
oncology infusion and referral scheduling workflows. No real order data, PHI, or
Epic data is used.

Live demo: see the deployed link in the repo description.

Stack: Python, Flask, LLM prompt chain, rules engine, inline SVG/HTML dashboard.
