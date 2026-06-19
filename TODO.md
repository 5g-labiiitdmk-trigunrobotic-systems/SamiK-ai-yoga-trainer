# TODO - Admin/User Login + Registration Approval

- [ ] Update `login.html` to add an **Admin login panel** on the same page (password `trigun2025`).


- [ ] Update `login.html` registration flow to set `status: "approving"` (instead of auto-approving).
- [ ] Update `login.html` normal user login to allow only `status === "approved"`; block `pending/hold/denied` with message.
- [ ] Update `login.html` normal user redirect to `index.html`.
- [ ] Update `admin.html` to manage registration statuses: **approve / deny / hold** in Members table.
- [ ] Update `admin.html` to include statuses in UI (e.g., badges) and default filter to Pending.
- [ ] Update `admin.html` action buttons to include: approve/deny/hold (keep delete).
- [ ] Ensure `admin.html` references correct filenames: `login.html` and `index.html`.
- [ ] Quick manual test: register user -> admin approve -> user login works; admin deny/hold -> user login blocked.

