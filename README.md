# Retouren-Plattform

## Einleitung

Diese Ausarbeitung wurde im Rahmen des Moduls Fallstudie Informationssysteme verfasst. Ziel des Moduls ist es, eigenständig Lösungsansätze für Aufgaben aus dem Bereich der Datenbankentwicklung und der Datenanalyse sowie der Konzeption von Informationssystemen zu entwickeln. Die Ausarbeitung erfolgt in Kleingruppen und somit ist die Planung und Kommunikation der Arbeits- und Zeiteinteilung auch Teil des Moduls. Das Ergebnis der Fallstudie werden über verschiedene Medienformen kommuniziert.

## Problemstellung

In der Fallstudie, soll in einem Pilotprojekt die „Letze Meile“ der Paketauslieferung optimiert werden. Durch den stetig steigenden Anstieg des Paketaufkommens von ca. 56% in der letzten Dekade kommt es bei der Auslieferung der Pakete in Ballungsräumen vermehrt zu Problemen bzw. zu negativen Auswirkungen (Bundesverband Paket und Expresslogistik e.V. (BIEK), 2020). 

Die Logistikunternehmen sammeln ihre Pakete in den Distributionszentren und verteilen diese dann auf die Zustellfahrzeuge, die diese wiederum zu den Kunden transportieren. Der gebündelte Transport zu den einzelnen Zentren ist dabei ökologisch, wohingegen der Transport zu den Kunden zu hohen Emissionen, Verkehrsbelastung und hohen Kosten führt. Berücksichtigt man die Vielzahl unterschiedlicher Transportdienstleister, summiert sich eine beachtliche Menge an Zustellfahrzeugen auf. Zusätzlich zu der entstehenden Umweltbelastung, entstehen Probleme bei der Zustellung, da Parkplätze innerhalb von Großstädten meist nicht vor entsprechender Zustelladresse vorhanden sind.

## Aufgabenstellung

Um die oben genannten Probleme zu minimieren, wird im Rahmen der Fallstudie der Einsatz einer Logistikplattform, „City Hubs“, erarbeitet. Hierbei soll der City Hub eine einheitliche Zustellung aller Pakete in einem definierten Bezirk durch einen Versanddienstleister ermöglichen. Die Aufgabenstellung des City Hubs unterteilt sich dabei in die folgenden sieben Module:

1. Paketdisposition, 
2. Empfängerportal, 
3. Lieferantenportal, 
4. Stadtportal, 
5. Zusteller-Portal, 
6. Mobile Zustellbasen und
7. Retoure.

## Beschreibung des Modules

Diese Ausarbeitung thematisiert das Retouren-Modul. Über eine Retouren-Plattform können in den mobilen Zustellbasen Retouren abgegeben werden. Abhängig vom Routing der Zustellbasis kalkuliert die Plattform, wann Absender Retouren in die mobile Zustellbasis einlegen können. Es werden beim Start vom Depot aus allerdings keine Fächer leer gelassen, Retouren können also nur in Fächer eingelegt werden, aus denen Empfänger Pakete abgeholt haben.
Ziel des folgenden Konzeptes ist somit die Ausarbeitung einer Retouren-Plattform, über welche Kunden ihre Pakete an den mobilen Zustellbasen als Retouren abfragen und anmelden können. Dabei soll diese Plattform die Orte der Zustellbasen und deren Kapazität erfassen, regulieren und steuern.

## Setup, Kollaborations- und Kommunikationstools 

Der Fallstudie erfolgt in Kleingruppen. Zur Planung und Kommunikation der Arbeits- und Zeiteinteilung wurde das folgende Setup bzw. wurden die folgenden Tools benutzt:

- Notion zum Protokollieren des Projektfortschrittes sowie als allgemeine Projektmanagementtool. Projektaufgaben wurden auf einem Kanban-Board erfasst und visualisiert; den möglichen Zuständen waren dabei {„Backlog“, „Active“,“Pending“,“Resolved“}. Eine Kopie des Protokolls und des Kanban-Boards steht als Markdown- bzw. HTML-Datei zur Verfügung. 
- Dropbox zum Speichern, Austausch und Versionsverwaltung der Projektdateien. 
- Git bzw. GitHub Repository zur Versionsverwaltung lokaler Kopien des Projektes. Eine Kopie der Dateien ist unter der folgenden Repository zu finden: https://github.com/luiul/retouren-plattform 
- Camunda BPM zur Geschäftsprozessmodellierung. Camunda BPM bietet auch ein open-source Workflow-Management-System an. Dieses System kann später im Projekt verwendet werden, beispielweise in der Implementierungsphase. 
- MySQLWorkbench zur Datenmodellierung. MySQLWorkbench bietet das Exportieren des ER-Diagramms als Forward Engineer SQL CREATE Skript an. Diese Software sowie das Skript kann später im Projekt verwendet werden, beispielweise in der Implementierungsphase.
- Draw.io zur Visualisierung der verschiedenen Modelle. 
- MS Word zum Verfassen und Formatieren des Konzeptes. Eine Kopie sämtliche Diagramme bzw. Abbildungen ist im Anhang zu finden. 
