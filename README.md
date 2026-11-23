# Sferapolis Control

This review copy describes the deployment architecture for a web application.
An HTTP reverse proxy serves the frontend and forwards API requests to an application
backend. The backend and its data services communicate over a private container
network. Administrative access is handled separately from the public interface.

The original repository records deployment and migration decisions, access controls
and operational verification. This copy contains an architecture overview only.
