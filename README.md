FM-Radioempfänger mit GNU Radio
---------------------------------

Dieses Projekt zeigt, wie man mit GNU Radio einen FM-Radioempfänger bauen kann, um Radiosignale zu empfangen und wiederzugeben.

Der FM-Radioempfänger verwendet GNU Radio, um Radiosignale von einer Datei zu empfangen, sie zu demodulieren und das Audiosignal über die Soundkarte wiederzugeben. 


Der Advanced File Source Block liest die Datei "radio.dat" ein und sein Ausgang wird mit dem Signal Source Block multipliziert. Das resultierende Signal durchläuft einen Tiefpassfilter, bevor es zum Demodulator gelangt. Die Ausgangssignale des Demodulators werden dann an drei Ziele weitergeleitet: den Waterfall Sink, den Frequency Sink und den Audio Sink.