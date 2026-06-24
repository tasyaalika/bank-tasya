body {
  background: #f0f4f8;
  font-family: 'Segoe UI', Roboto, system-ui, -apple-system, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  margin: 20px;
}

/* kartu utama – mirip seperti gambar dengan sentuhan modern */
.card {
  max-width: 780px;
  width: 100%;
  background: white;
  border-radius: 40px 40px 40px 40px;
  box-shadow: 0 20px 40px rgba(0, 20, 30, 0.12), 0 8px 16px rgba(0,0,0,0.05);
  padding: 2rem 2.5rem 2.8rem;
  transition: all 0.2s ease;
  border: 1px solid rgba(0, 80, 130, 0.08);
}

/* header: BANK TASYA dengan gaya bold */
.bank-header {
  text-align: center;
  margin-bottom: 1.2rem;
}

.bank-name {
  font-size: 3.2rem;
  font-weight: 700;
  letter-spacing: 1px;
  color: #0b2d4b;
  text-transform: uppercase;
  line-height: 1.1;
}
.bank-name span {
  color: #1a6b8a;
}

.tagline {
  font-size: 1.4rem;
  font-weight: 500;
  color: #1f4b6e;
  letter-spacing: 0.5px;
  margin-top: -0.2rem;
  border-top: 3px double #9bc5d9;
  display: inline-block;
  padding-top: 0.3rem;
  padding-inline: 1rem;
}

/* sub tagline: melayani dengan hati ... */
.sub-tagline {
  text-align: center;
  font-weight: 400;
  color: #1c4c6b;
  background: #e8f0f7;
  padding: 0.5rem 1rem;
  border-radius: 60px;
  font-size: 1.1rem;
  margin: 0.5rem 0 1.8rem 0;
  display: inline-block;
  width: auto;
  margin-left: auto;
  margin-right: auto;
  letter-spacing: 0.3px;
  backdrop-filter: blur(2px);
  box-shadow: inset 0 1px 4px rgba(255,255,255,0.8);
}

.sub-tagline i {
  margin-right: 6px;
  color: #1f7a9e;
}

/* intro teks */
.intro-text {
  font-size: 1.05rem;
  color: #1d3c53;
  text-align: center;
  background: #f5faff;
  padding: 0.8rem 1.2rem;
  border-radius: 60px;
  margin-bottom: 2rem;
  border: 1px solid #cde0ed;
  font-weight: 400;
  box-shadow: 0 2px 4px rgba(0,0,0,0.02);
}

/* grid 3 pilar: aman, terpercaya, bertumbuh */
.pillars {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1.2rem 2rem;
  margin: 2rem 0 2.4rem 0;
}

.pillar-item {
  flex: 1 0 120px;
  text-align: center;
  background: #fafdff;
  padding: 0.9rem 0.5rem;
  border-radius: 30px;
  box-shadow: 0 4px 8px rgba(0, 40, 70, 0.04);
  border: 1px solid #dcebf5;
  transition: 0.1s ease;
  min-width: 100px;
}
.pillar-item i {
  font-size: 1.6rem;
  color: #1b6c8f;
  background: #e3eff8;
  padding: 10px;
  border-radius: 50%;
  width: 48px;
  height: 48px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 6px;
}
.pillar-item h3 {
  font-size: 1.3rem;
  font-weight: 700;
  color: #10344b;
  letter-spacing: 0.3px;
  margin: 4px 0 2px;
}
.pillar-item p {
  font-size: 0.85rem;
  color: #2e5a77;
  font-weight: 400;
  margin: 0;
  padding: 0 4px;
  line-height: 1.3;
}

/* CEO section */
.ceo-section {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  gap: 1.2rem 1.5rem;
  flex-wrap: wrap;
  margin: 2.2rem 0 2rem 0;
  background: #eef5fc;
  padding: 0.8rem 2rem 0.8rem 1.8rem;
  border-radius: 60px;
  border-left: 4px solid #1b7b9e;
}

.ceo-avatar {
  background: #1f5f7a;
  color: white;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2rem;
  font-weight: 500;
  box-shadow: 0 6px 10px rgba(0,40,60,0.1);
  background: linear-gradient(145deg, #196a8a, #0d4a66);
}

.ceo-info {
  display: flex;
  flex-direction: column;
}
.ceo-info .name {
  font-size: 1.5rem;
  font-weight: 700;
  color: #083045;
  letter-spacing: 0.3px;
}
.ceo-info .title {
  font-size: 0.9rem;
  font-weight: 500;
  color: #1e5f7a;
  background: white;
  padding: 0.1rem 1rem;
  border-radius: 30px;
  display: inline-block;
  width: fit-content;
  margin-top: 2px;
  border: 1px solid #bcd3e5;
}

/* partner line */
.partner-line {
  font-size: 1.05rem;
  font-weight: 500;
  color: #103b52;
  text-align: center;
  background: #e5f0fa;
  padding: 0.6rem 1.2rem;
  border-radius: 60px;
  margin: 1.2rem 0 2rem 0;
  border: 1px solid #c5dae9;
  letter-spacing: 0.3px;
}
.partner-line i {
  margin-right: 8px;
  color: #106b8a;
}

/* footer: kontak & lokasi */
.contact-footer {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  background: #dcecf5;
  padding: 1.2rem 1.8rem;
  border-radius: 50px;
  margin-top: 1.2rem;
  gap: 0.8rem 1.5rem;
  border: 1px solid #b6d2e5;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 6px 12px;
  flex-wrap: wrap;
  font-size: 0.95rem;
  color: #023047;
}
.contact-item i {
  font-size: 1.2rem;
  color: #0b5c7a;
  width: 24px;
  text-align: center;
}
.contact-item a {
  color: #013142;
  text-decoration: none;
  font-weight: 500;
  border-bottom: 1px dotted rgba(0,60,90,0.2);
}
.contact-item a:hover {
  border-bottom: 2px solid #12688a;
  color: #001f2e;
}

.website {
  font-weight: 600;
  color: #08384e;
  background: white;
  padding: 0.3rem 1.2rem;
  border-radius: 40px;
  font-size: 0.9rem;
  border: 1px solid #9abed4;
}
.website i {
  margin-right: 6px;
  color: #12688a;
}

/* Nama Tasya Alika ditampilkan secara halus */
.nama-tasya {
  text-align: center;
  font-size: 0.9rem;
  color: #265d79;
  margin: 1.5rem 0 0.2rem 0;
  letter-spacing: 0.3px;
  font-weight: 400;
  background: #f1f9ff;
  padding: 0.3rem 1.5rem;
  border-radius: 40px;
  display: inline-block;
  width: auto;
  margin-left: auto;
  margin-right: auto;
  border: 1px solid #bcd6e8;
}
.nama-tasya strong {
  font-weight: 600;
  color: #003553;
}

/* responsif */
@media (max-width: 600px) {
  .card {
    padding: 1.5rem 1.2rem;
  }
  .bank-name {
    font-size: 2.4rem;
  }
  .tagline {
    font-size: 1.1rem;
  }
  .pillars {
    gap: 0.8rem;
  }
  .contact-footer {
    flex-direction: column;
    align-items: flex-start;
    border-radius: 30px;
    padding: 1.2rem 1.5rem;
  }
  .ceo-section {
    flex-direction: column;
    align-items: flex-start;
    border-radius: 40px;
    padding: 1.2rem 1.5rem;
  }
  .sub-tagline {
    font-size: 0.95rem;
    padding: 0.4rem 1rem;
  }
}
