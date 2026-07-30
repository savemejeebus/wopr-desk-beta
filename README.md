# wopr-desk-beta

Built static assets for the WOPR desk app (beta). Deployed from the
private WOPR repo by `services/deploy-desk/deploy.sh` — do not edit here;
every deploy force-pushes this branch. Data access requires a Supabase
login; the anon key in the bundle is public by design (RLS enforces
access).
