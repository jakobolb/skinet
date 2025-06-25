# Skinet – E‑Commerce Musterprojekt

## 📌 Beschreibung

Dies ist das aktualisierte **Full-Stack E-Commerce Beispiel** auf Basis von:

- **.NET 7**
- **Angular 15**
- **Bootstrap 5**

Das Projekt stammt aus dem Udemy-Kurs von **Neil Cummings**.

🔗 **Originalquelle:** [TryCatchLearn/Skinet3.1](https://github.com/TryCatchLearn/Skinet3.1)

## 🚀 Schnellstart

1. Clone das Repo:

   ```bash
   git clone https://github.com/jakobolb/skinet.git
   ```
2. .NET- und Node-Abhängigkeiten installieren:

   ```bash
   cd skinet
   dotnet restore
   cd client && npm install
   ```
3. SQL Server & Redis via Docker starten:

   ```bash
   docker-compose up -d
   ```
4. Stripe-Keys in `API/appsettings.json` hinterlegen (Publishable, Secret & Webhook Secret).
5. (Optional) SSL-Zertifikate lokal mit mkcert generieren.
6. App starten:

   * Backend: `cd API && dotnet run`
   * Frontend: `cd client && ng serve --ssl …`
7. Zugriff über:

   * API/Swagger: `https://localhost:5001/swagger`
   * Frontend: `https://localhost:4200`


[1]: https://github.com/TryCatchLearn/skinet?utm_source=chatgpt.com "TryCatchLearn/skinet - GitHub"
[2]: https://www.facebook.com/groups/netcorevn/posts/4071204163112775/?utm_source=chatgpt.com "Cho em xin cách hiểu của anh chị về UnitOfWork, DBcontext đi ạ ..."
[3]: https://github.com/TryCatchLearn/skinet-2024?utm_source=chatgpt.com "TryCatchLearn/skinet-2024 - GitHub"
[4]: https://www.trycatchlearn.com/tutorials/skinet-setup-tutorial?utm_source=chatgpt.com "Skinet setup tutorial - TryCatchLearn"
