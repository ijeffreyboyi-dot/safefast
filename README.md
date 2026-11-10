# SafeFast Rx (صيامٌ آمن)

Clinical decision support prototype that helps doctors build a medication plan for chronic patients before Ramadan. Demo only: all patient data is synthetic.

- `index.html`: all views (hospital system, doctor, pharmacist, clinic dashboard, settings, patient phone)
- `doctor.html`, `pharm.html`, `patient.html`: single-role entry points
- Sync across devices uses Firebase Firestore (`config.js`); `firestore.rules` limits writes to the demo collections.
