# PanicTranslate

Convert chaotic, panicked messages into clear, structured emergency reports for faster and safer response.

## Overview

PanicTranslate is an AI-powered tool that transforms unstructured panic messages into structured emergency reports.

It helps:
- Extract critical information
- Reduce confusion
- Enable faster decision-making in emergencies

## Features

- Fact Extraction
  - Identifies incident type, location, victims, and hazards

- Structured Triage
  - Converts raw input into a standardized format

- Severity Classification
  - Rates incidents on a 1–5 scale

- Responder Briefing
  - Generates a concise and actionable summary

- Safety-Oriented Design
  - Highlights critical risks like electrical hazards

## How It Works

1. User enters a panic message
2. System processes natural language
3. Extracts key details
4. Assigns severity level
5. Generates structured report and briefing

## Example

Input:
Oh my god help!! Room 317 there’s water leaking and sparks coming from the light!!
My friend got shocked and he’s not moving properly please hurry!!

Output:

Structured Facts:
- Incident Type: Electrical shock, water leak, electrical hazard
- Location: Room 317
- Number of People Affected: 1
- Severity: 5 (Life-threatening)
- Immediate Needs: Medical assistance, power shut-off, water control

Responder Briefing:
Emergency medical and electrical teams are required in Room 317 for an electrical shock victim and an active water leak with sparks. Immediate intervention required.

## Limitations

- Not a replacement for emergency services
- May misinterpret unclear or incomplete input
- Requires human verification

Always confirm critical details before taking action.

## Future Improvements

- Confidence scoring for extracted data
- Priority-based dispatch system
- Multi-language support
- Voice input support
- Real-time caller guidance

## Tech Stack

- Frontend: React / Next.js
- Backend: Node.js
- AI: LLM-based parsing
- Deployment: Vercel

## Getting Started

git clone https://github.com/your-username/panictranslate.git
cd panictranslate
npm install
npm run dev

## Demo

https://panictranslate-sc.vercel.app

## Contributing

Pull requests are welcome. For major changes, open an issue first.

## License

MIT License

## Note

This is a decision-support tool, not an automated authority.

Always validate outputs before acting.
