<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ClipForge — Auto Clip for TikTok & Instagram</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&family=Space+Grotesk:wght@400;500;700&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #0a0a0f;
    --surface: #111118;
    --surface2: #1a1a25;
    --border: #2a2a3a;
    --accent: #7c5cfc;
    --accent2: #fc5c9c;
    --accent-glow: rgba(124,92,252,0.25);
    --text: #f0f0f8;
    --muted: #8888aa;
    --success: #3dd68c;
    --warning: #fbbf24;
    --font-display: 'Space Grotesk', sans-serif;
    --font-body: 'Inter', sans-serif;
    --radius: 12px;
    --radius-sm: 8px;
  }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--font-body);
    font-size: 15px;
    line-height: 1.6;
    min-height: 100vh;
  }

  /* HEADER */
  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 40px;
    border-bottom: 1px solid var(--border);
    background: rgba(10,10,15,0.95);
    position: sticky;
    top: 0;
    z-index: 100;
    backdrop-filter: blur(12px);
  }

  .logo {
    font-family: var(--font-display);
    font-size: 22px;
    font-weight: 700;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    letter-spacing: -0.5px;
  }

  .badge {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 4px 14px;
    font-size: 12px;
    color: var(--muted);
    font-weight: 500;
  }

  /* HERO */
  .hero {
    text-align: center;
    padding: 60px 40px 40px;
    max-width: 700px;
    margin: 0 auto;
  }

  .hero h1 {
    font-family: var(--font-display);
    font-size: clamp(32px, 5vw, 52px);
    font-weight: 700;
    line-height: 1.1;
    letter-spacing: -1px;
    margin-bottom: 16px;
  }

  .hero h1 span {
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero p {
    color: var(--muted);
    font-size: 16px;
    max-width: 480px;
    margin: 0 auto 32px;
  }

  .platform-pills {
    display: flex;
    gap: 10px;
    justify-content: center;
    margin-bottom: 40px;
  }

  .pill {
    display: flex;
    align-items: center;
    gap: 6px;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 6px 16px;
    font-size: 13px;
    font-weight: 500;
    color: var(--muted);
  }

  .pill-dot { width: 7px; height: 7px; border-radius: 50%; }
  .pill-tiktok .pill-dot { background: #69C9D0; }
  .pill-insta .pill-dot { background: var(--accent2); }
  .pill-youtube .pill-dot { background: #FF4444; }

  /* MAIN CARD */
  .main { max-width: 900px; margin: 0 auto; padding: 0 24px 60px; }

  .card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 16px;
    overflow: hidden;
    margin-bottom: 24px;
  }

  .card-header {
    padding: 20px 24px;
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .card-icon {
    width: 32px; height: 32px;
    background: var(--accent-glow);
    border: 1px solid var(--accent);
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 15px;
  }

  .card-title {
    font-family: var(--font-display);
    font-size: 16px;
    font-weight: 600;
  }

  .card-body { padding: 24px; }

  /* UPLOAD ZONE */
  .upload-zone {
    border: 2px dashed var(--border);
    border-radius: var(--radius);
    padding: 60px 24px;
    text-align: center;
    cursor: pointer;
    transition: all 0.2s;
    position: relative;
  }

  .upload-zone:hover, .upload-zone.dragover {
    border-color: var(--accent);
    background: var(--accent-glow);
  }

  .upload-zone input[type=file] {
    position: absolute; inset: 0; opacity: 0; cursor: pointer; width: 100%; height: 100%;
  }

  .upload-icon { font-size: 48px; margin-bottom: 16px; }

  .upload-zone h3 {
    font-family: var(--font-display);
    font-size: 18px;
    font-weight: 600;
    margin-bottom: 8px;
  }

  .upload-zone p { color: var(--muted); font-size: 14px; }

  .upload-btn {
    display: inline-block;
    margin-top: 16px;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    color: white;
    border: none;
    border-radius: var(--radius-sm);
    padding: 10px 24px;
    font-size: 14px;
    font-weight: 600;
    cursor: pointer;
    font-family: var(--font-body);
    pointer-events: none;
  }

  /* VIDEO PREVIEW */
  #video-preview-section { display: none; }

  video {
    width: 100%;
    border-radius: var(--radius-sm);
    background: #000;
    max-height: 300px;
    object-fit: contain;
  }

  .video-meta {
    display: flex;
    gap: 16px;
    margin-top: 12px;
    flex-wrap: wrap;
  }

  .meta-item {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: 13px;
    color: var(--muted);
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 4px 12px;
  }

  /* SETTINGS */
  .settings-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 16px;
  }

  @media (max-width: 600px) { .settings-grid { grid-template-columns: 1fr; } }

  .setting-group label {
    display: block;
    font-size: 13px;
    font-weight: 500;
    color: var(--muted);
    margin-bottom: 8px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  .setting-group select, .setting-group input[type=number], .setting-group input[type=range] {
    width: 100%;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    color: var(--text);
    font-family: var(--font-body);
    font-size: 14px;
    padding: 10px 14px;
    appearance: none;
    outline: none;
    transition: border-color 0.2s;
  }

  .setting-group select:focus, .setting-group input:focus {
    border-color: var(--accent);
  }

  .toggle-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 12px 0;
    border-bottom: 1px solid var(--border);
  }

  .toggle-row:last-child { border-bottom: none; }

  .toggle-label { font-size: 14px; font-weight: 500; }
  .toggle-desc { font-size: 12px; color: var(--muted); margin-top: 2px; }

  .toggle {
    width: 40px; height: 22px;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 11px;
    cursor: pointer;
    position: relative;
    transition: background 0.2s;
    flex-shrink: 0;
  }

  .toggle.on { background: var(--accent); border-color: var(--accent); }

  .toggle::after {
    content: '';
    position: absolute;
    width: 16px; height: 16px;
    background: white;
    border-radius: 50%;
    top: 2px; left: 2px;
    transition: transform 0.2s;
  }

  .toggle.on::after { transform: translateX(18px); }

  /* TIMELINE */
  #timeline-section { display: none; }

  .timeline-bar {
    width: 100%;
    height: 60px;
    background: var(--surface2);
    border-radius: var(--radius-sm);
    position: relative;
    overflow: hidden;
    border: 1px solid var(--border);
    cursor: pointer;
    margin-bottom: 16px;
  }

  .timeline-track {
    position: absolute;
    height: 100%;
    background: linear-gradient(135deg, rgba(124,92,252,0.4), rgba(252,92,156,0.4));
    border-left: 2px solid var(--accent);
    border-right: 2px solid var(--accent2);
    cursor: ew-resize;
  }

  .timeline-label {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 11px;
    font-weight: 600;
    color: white;
    pointer-events: none;
    white-space: nowrap;
  }

  .clips-info {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    margin-bottom: 16px;
  }

  .clip-badge {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 4px 12px;
    font-size: 13px;
    color: var(--muted);
  }

  .clip-badge span { color: var(--text); font-weight: 600; }

  /* GENERATE BUTTON */
  .generate-btn {
    width: 100%;
    padding: 16px;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    color: white;
    border: none;
    border-radius: var(--radius);
    font-size: 16px;
    font-weight: 700;
    font-family: var(--font-display);
    cursor: pointer;
    transition: opacity 0.2s, transform 0.1s;
    letter-spacing: -0.3px;
  }

  .generate-btn:hover { opacity: 0.9; transform: translateY(-1px); }
  .generate-btn:active { transform: translateY(0); }
  .generate-btn:disabled { opacity: 0.4; cursor: not-allowed; transform: none; }

  /* PROGRESS */
  #progress-section { display: none; }

  .progress-wrap {
    background: var(--surface2);
    border-radius: 100px;
    height: 8px;
    overflow: hidden;
    margin-bottom: 12px;
  }

  .progress-bar {
    height: 100%;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    border-radius: 100px;
    width: 0%;
    transition: width 0.3s ease;
  }

  .progress-text { font-size: 13px; color: var(--muted); text-align: center; }

  .log-box {
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 16px;
    font-size: 12px;
    font-family: monospace;
    color: var(--muted);
    max-height: 120px;
    overflow-y: auto;
    margin-top: 16px;
  }

  .log-line { margin-bottom: 4px; }
  .log-ok { color: var(--success); }
  .log-info { color: var(--accent); }

  /* CLIPS OUTPUT */
  #clips-section { display: none; }

  .clips-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 16px;
  }

  .clip-card {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    overflow: hidden;
    transition: border-color 0.2s, transform 0.2s;
  }

  .clip-card:hover { border-color: var(--accent); transform: translateY(-2px); }

  .clip-preview {
    position: relative;
    background: #000;
    aspect-ratio: 9/16;
    overflow: hidden;
  }

  .clip-preview video {
    width: 100%; height: 100%;
    object-fit: cover;
    border-radius: 0;
    max-height: none;
  }

  .clip-overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(to top, rgba(0,0,0,0.7) 0%, transparent 50%);
    display: flex;
    align-items: flex-end;
    padding: 12px;
  }

  .clip-number {
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    color: white;
    font-size: 11px;
    font-weight: 700;
    border-radius: 4px;
    padding: 2px 8px;
  }

  .clip-info { padding: 12px; }

  .clip-name {
    font-size: 13px;
    font-weight: 600;
    margin-bottom: 4px;
  }

  .clip-duration { font-size: 12px; color: var(--muted); margin-bottom: 12px; }

  .clip-actions { display: flex; gap: 8px; }

  .btn-download, .btn-play {
    flex: 1;
    padding: 8px;
    border-radius: var(--radius-sm);
    border: none;
    font-size: 12px;
    font-weight: 600;
    cursor: pointer;
    text-decoration: none;
    text-align: center;
    font-family: var(--font-body);
    transition: opacity 0.2s;
  }

  .btn-download {
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    color: white;
  }

  .btn-play {
    background: var(--surface);
    border: 1px solid var(--border);
    color: var(--text);
  }

  .btn-download:hover, .btn-play:hover { opacity: 0.8; }

  /* PLATFORM FORMAT GUIDE */
  .format-guide {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
    margin-top: 0;
  }

  .format-card {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 16px;
  }

  .format-name {
    font-size: 13px;
    font-weight: 700;
    margin-bottom: 8px;
    display: flex;
    align-items: center;
    gap: 6px;
  }

  .format-detail { font-size: 12px; color: var(--muted); line-height: 1.8; }

  /* CAPTION OVERLAY OPTION */
  .caption-preview {
    background: #000;
    border-radius: var(--radius-sm);
    aspect-ratio: 9/16;
    max-width: 160px;
    position: relative;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .caption-text-preview {
    color: white;
    font-size: 16px;
    font-weight: 900;
    text-align: center;
    padding: 12px;
    text-shadow: 2px 2px 0 #000;
    font-family: var(--font-display);
    line-height: 1.2;
  }

  /* NOTIFICATION */
  .toast {
    position: fixed;
    bottom: 24px;
    right: 24px;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 14px 20px;
    font-size: 14px;
    font-weight: 500;
    display: flex;
    align-items: center;
    gap: 10px;
    transform: translateY(100px);
    transition: transform 0.3s;
    z-index: 9999;
    box-shadow: 0 8px 32px rgba(0,0,0,0.5);
  }

  .toast.show { transform: translateY(0); }
  .toast-icon { font-size: 18px; }

  hr.divider { border: none; border-top: 1px solid var(--border); margin: 20px 0; }

  .section-label {
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--muted);
    font-weight: 600;
    margin-bottom: 16px;
  }

  /* ── SOCIAL ACCOUNTS ── */
  .social-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 14px;
    margin-bottom: 20px;
  }

  .social-account-card {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 16px;
    display: flex;
    flex-direction: column;
    gap: 12px;
    transition: border-color 0.2s;
    position: relative;
  }

  .social-account-card.connected { border-color: var(--success); }
  .social-account-card.connected::before {
    content: '✓';
    position: absolute;
    top: 10px; right: 12px;
    font-size: 12px;
    font-weight: 700;
    color: var(--success);
  }

  .social-platform-header {
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .platform-logo {
    width: 36px; height: 36px;
    border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
    flex-shrink: 0;
  }

  .platform-logo.tiktok { background: #010101; }
  .platform-logo.instagram { background: linear-gradient(135deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888); }
  .platform-logo.youtube { background: #FF0000; }
  .platform-logo.twitter { background: #000; }
  .platform-logo.facebook { background: #1877F2; }

  .platform-name { font-size: 14px; font-weight: 600; }
  .platform-status { font-size: 11px; color: var(--muted); }
  .platform-status.ok { color: var(--success); }

  .connect-btn {
    width: 100%;
    padding: 8px;
    border-radius: var(--radius-sm);
    border: 1px solid var(--border);
    background: var(--surface);
    color: var(--text);
    font-size: 12px;
    font-weight: 600;
    cursor: pointer;
    font-family: var(--font-body);
    transition: all 0.2s;
  }

  .connect-btn:hover { border-color: var(--accent); color: var(--accent); }
  .connect-btn.connected { background: rgba(61,214,140,0.1); border-color: var(--success); color: var(--success); }

  .account-username {
    font-size: 12px;
    color: var(--muted);
    display: none;
  }

  .social-account-card.connected .account-username { display: block; }

  /* ── MODAL ── */
  .modal-backdrop {
    display: none;
    position: fixed; inset: 0;
    background: rgba(0,0,0,0.75);
    z-index: 500;
    align-items: center;
    justify-content: center;
  }

  .modal-backdrop.open { display: flex; }

  .modal {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 18px;
    padding: 32px;
    width: 90%;
    max-width: 420px;
    position: relative;
    animation: modalIn 0.2s ease;
  }

  @keyframes modalIn { from { opacity:0; transform: scale(0.95) translateY(12px); } to { opacity:1; transform: none; } }

  .modal-close {
    position: absolute;
    top: 16px; right: 16px;
    background: var(--surface2);
    border: 1px solid var(--border);
    color: var(--muted);
    width: 30px; height: 30px;
    border-radius: 50%;
    cursor: pointer;
    font-size: 16px;
    display: flex; align-items: center; justify-content: center;
  }

  .modal-close:hover { color: var(--text); }

  .modal-logo {
    width: 52px; height: 52px;
    border-radius: 14px;
    display: flex; align-items: center; justify-content: center;
    font-size: 26px;
    margin-bottom: 16px;
  }

  .modal h2 {
    font-family: var(--font-display);
    font-size: 20px;
    font-weight: 700;
    margin-bottom: 6px;
  }

  .modal p { font-size: 13px; color: var(--muted); margin-bottom: 20px; }

  .modal-field { margin-bottom: 14px; }

  .modal-field label {
    display: block;
    font-size: 12px;
    font-weight: 600;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 6px;
  }

  .modal-field input {
    width: 100%;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    color: var(--text);
    font-family: var(--font-body);
    font-size: 14px;
    padding: 10px 14px;
    outline: none;
    transition: border-color 0.2s;
  }

  .modal-field input:focus { border-color: var(--accent); }

  .modal-footer { display: flex; gap: 10px; margin-top: 20px; }

  .btn-primary {
    flex: 1;
    padding: 11px;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    color: white;
    border: none;
    border-radius: var(--radius-sm);
    font-size: 14px;
    font-weight: 700;
    font-family: var(--font-display);
    cursor: pointer;
    transition: opacity 0.2s;
  }

  .btn-primary:hover { opacity: 0.88; }

  .btn-secondary {
    padding: 11px 18px;
    background: var(--surface2);
    border: 1px solid var(--border);
    color: var(--muted);
    border-radius: var(--radius-sm);
    font-size: 14px;
    font-weight: 600;
    font-family: var(--font-body);
    cursor: pointer;
  }

  .oauth-note {
    font-size: 11px;
    color: var(--muted);
    margin-top: 12px;
    text-align: center;
    line-height: 1.5;
  }

  /* ── SCHEDULER ── */
  .scheduler-section { display: none; }

  .schedule-clips-list { display: flex; flex-direction: column; gap: 12px; margin-bottom: 20px; }

  .schedule-clip-row {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 14px 16px;
    display: grid;
    grid-template-columns: 40px 1fr auto;
    gap: 12px;
    align-items: center;
  }

  .schedule-clip-thumb {
    width: 40px; height: 40px;
    border-radius: 6px;
    background: var(--bg);
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
  }

  .schedule-clip-info { display: flex; flex-direction: column; gap: 4px; }
  .schedule-clip-name { font-size: 13px; font-weight: 600; }
  .schedule-clip-time { font-size: 12px; color: var(--muted); }

  .schedule-clip-controls {
    display: flex;
    flex-direction: column;
    gap: 6px;
    align-items: flex-end;
  }

  .schedule-datetime {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    color: var(--text);
    font-family: var(--font-body);
    font-size: 12px;
    padding: 6px 10px;
    outline: none;
    cursor: pointer;
    transition: border-color 0.2s;
    width: 100%;
  }

  .schedule-datetime:focus { border-color: var(--accent); }

  .schedule-platforms {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
  }

  .platform-chip {
    padding: 3px 10px;
    border-radius: 20px;
    font-size: 11px;
    font-weight: 600;
    border: 1px solid var(--border);
    background: var(--surface);
    color: var(--muted);
    cursor: pointer;
    transition: all 0.15s;
    user-select: none;
  }

  .platform-chip.selected { border-color: var(--accent); background: var(--accent-glow); color: var(--text); }
  .platform-chip:hover { border-color: var(--accent); }

  .caption-input {
    width: 100%;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    color: var(--text);
    font-family: var(--font-body);
    font-size: 13px;
    padding: 10px 12px;
    outline: none;
    resize: vertical;
    min-height: 60px;
    transition: border-color 0.2s;
    margin-top: 8px;
  }

  .caption-input:focus { border-color: var(--accent); }

  .char-count { font-size: 11px; color: var(--muted); text-align: right; margin-top: 4px; }

  .schedule-queue {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    overflow: hidden;
    margin-top: 20px;
  }

  .queue-header {
    padding: 12px 16px;
    border-bottom: 1px solid var(--border);
    font-size: 13px;
    font-weight: 600;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .queue-count {
    background: var(--accent);
    color: white;
    font-size: 11px;
    font-weight: 700;
    border-radius: 10px;
    padding: 1px 8px;
  }

  .queue-item {
    padding: 12px 16px;
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    gap: 12px;
    font-size: 13px;
  }

  .queue-item:last-child { border-bottom: none; }

  .queue-status {
    width: 8px; height: 8px;
    border-radius: 50%;
    background: var(--warning);
    flex-shrink: 0;
  }

  .queue-status.scheduled { background: var(--accent); animation: pulse 2s infinite; }
  .queue-status.posted { background: var(--success); animation: none; }

  @keyframes pulse { 0%,100%{opacity:1} 50%{opacity:0.4} }

  .queue-item-info { flex: 1; }
  .queue-item-name { font-weight: 600; margin-bottom: 2px; }
  .queue-item-meta { font-size: 11px; color: var(--muted); }

  .queue-item-remove {
    background: none;
    border: none;
    color: var(--muted);
    cursor: pointer;
    font-size: 16px;
    padding: 2px 6px;
    border-radius: 4px;
    transition: color 0.2s, background 0.2s;
  }

  .queue-item-remove:hover { color: #ff5555; background: rgba(255,85,85,0.1); }

  .connected-accounts-bar {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-bottom: 16px;
    padding: 12px 16px;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    align-items: center;
  }

  .connected-badge {
    display: flex;
    align-items: center;
    gap: 5px;
    background: rgba(61,214,140,0.12);
    border: 1px solid rgba(61,214,140,0.3);
    border-radius: 20px;
    padding: 4px 12px;
    font-size: 12px;
    font-weight: 600;
    color: var(--success);
  }

  .no-accounts-msg {
    font-size: 13px;
    color: var(--muted);
  }

  .schedule-all-btn {
    width: 100%;
    padding: 13px;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    color: white;
    border: none;
    border-radius: var(--radius);
    font-size: 15px;
    font-weight: 700;
    font-family: var(--font-display);
    cursor: pointer;
    transition: opacity 0.2s, transform 0.1s;
    margin-top: 16px;
  }

  .schedule-all-btn:hover { opacity: 0.9; transform: translateY(-1px); }
</style>
</head>
<body>

<header>
  <div class="logo">⚡ ClipForge</div>
  <div class="badge">TikTok & Instagram Ready</div>
</header>

<div class="hero">
  <h1>Turn any video into<br><span>viral short clips</span></h1>
  <p>Upload your video and ClipForge will automatically cut it into perfectly sized clips for TikTok and Instagram Reels.</p>
  <div class="platform-pills">
    <div class="pill pill-tiktok"><div class="pill-dot"></div> TikTok</div>
    <div class="pill pill-insta"><div class="pill-dot"></div> Instagram Reels</div>
    <div class="pill pill-youtube"><div class="pill-dot"></div> YouTube Shorts</div>
  </div>
</div>

<div class="main">

  <!-- UPLOAD -->
  <div class="card">
    <div class="card-header">
      <div class="card-icon">📁</div>
      <div class="card-title">Upload Your Video</div>
    </div>
    <div class="card-body">
      <div class="upload-zone" id="upload-zone">
        <input type="file" id="file-input" accept="video/*">
        <div class="upload-icon">🎬</div>
        <h3>Drop your video here</h3>
        <p>Supports MP4, MOV, AVI, WebM — up to any size</p>
        <div class="upload-btn">Choose File</div>
      </div>

      <div id="video-preview-section">
        <hr class="divider">
        <video id="video-player" controls></video>
        <div class="video-meta" id="video-meta"></div>
      </div>
    </div>
  </div>

  <!-- CLIP SETTINGS -->
  <div class="card" id="settings-card" style="display:none">
    <div class="card-header">
      <div class="card-icon">⚙️</div>
      <div class="card-title">Clip Settings</div>
    </div>
    <div class="card-body">
      <div class="settings-grid" style="margin-bottom:20px">
        <div class="setting-group">
          <label>Clip Duration</label>
          <select id="clip-duration">
            <option value="15">15 seconds</option>
            <option value="30" selected>30 seconds</option>
            <option value="45">45 seconds</option>
            <option value="60">60 seconds</option>
            <option value="90">90 seconds</option>
          </select>
        </div>
        <div class="setting-group">
          <label>Platform Format</label>
          <select id="platform-format">
            <option value="9:16">9:16 — TikTok / Reels</option>
            <option value="1:1">1:1 — Instagram Square</option>
            <option value="16:9">16:9 — YouTube / Landscape</option>
          </select>
        </div>
        <div class="setting-group">
          <label>Number of Clips</label>
          <select id="num-clips">
            <option value="3">3 clips</option>
            <option value="5" selected>5 clips</option>
            <option value="8">8 clips</option>
            <option value="10">10 clips</option>
            <option value="auto">Auto (max possible)</option>
          </select>
        </div>
        <div class="setting-group">
          <label>Clip Selection Mode</label>
          <select id="clip-mode">
            <option value="spread">Spread evenly</option>
            <option value="random">Random moments</option>
            <option value="start">From beginning</option>
            <option value="end">From end</option>
          </select>
        </div>
      </div>

      <hr class="divider">
      <div class="section-label">Enhancements</div>

      <div class="toggle-row">
        <div>
          <div class="toggle-label">Auto Captions</div>
          <div class="toggle-desc">Add animated text captions to each clip</div>
        </div>
        <div class="toggle on" id="toggle-captions" onclick="toggleOpt(this)"></div>
      </div>
      <div class="toggle-row">
        <div>
          <div class="toggle-label">Watermark Branding</div>
          <div class="toggle-desc">Add your channel name to clips</div>
        </div>
        <div class="toggle" id="toggle-watermark" onclick="toggleOpt(this)"></div>
      </div>
      <div class="toggle-row">
        <div>
          <div class="toggle-label">Auto Hashtags</div>
          <div class="toggle-desc">Generate relevant hashtags for each clip</div>
        </div>
        <div class="toggle on" id="toggle-hashtags" onclick="toggleOpt(this)"></div>
      </div>

      <div id="watermark-input" style="display:none; margin-top:12px">
        <div class="setting-group">
          <label>Channel / Brand Name</label>
          <input type="text" id="watermark-text" placeholder="e.g. @yourchannel" style="width:100%; background:var(--surface2); border:1px solid var(--border); border-radius:var(--radius-sm); color:var(--text); font-family:var(--font-body); font-size:14px; padding:10px 14px; outline:none;">
        </div>
      </div>
    </div>
  </div>

  <!-- TIMELINE -->
  <div class="card" id="timeline-section">
    <div class="card-header">
      <div class="card-icon">🎞️</div>
      <div class="card-title">Clip Preview</div>
    </div>
    <div class="card-body">
      <div class="clips-info" id="clips-info"></div>
      <div class="timeline-bar" id="timeline-bar">
        <div id="timeline-track" class="timeline-track"></div>
      </div>
      <button class="generate-btn" id="generate-btn" onclick="generateClips()">
        ✂️ Generate Clips
      </button>
    </div>
  </div>

  <!-- PROGRESS -->
  <div class="card" id="progress-section">
    <div class="card-header">
      <div class="card-icon">⚡</div>
      <div class="card-title">Processing</div>
    </div>
    <div class="card-body">
      <div class="progress-wrap">
        <div class="progress-bar" id="progress-bar"></div>
      </div>
      <div class="progress-text" id="progress-text">Preparing...</div>
      <div class="log-box" id="log-box"></div>
    </div>
  </div>

  <!-- OUTPUT CLIPS -->
  <div class="card" id="clips-section">
    <div class="card-header">
      <div class="card-icon">🎉</div>
      <div class="card-title">Your Clips are Ready!</div>
    </div>
    <div class="card-body">
      <div class="clips-grid" id="clips-grid"></div>
    </div>
  </div>

  <!-- PLATFORM GUIDE -->
  <div class="card">
    <div class="card-header">
      <div class="card-icon">📱</div>
      <div class="card-title">Platform Format Guide</div>
    </div>
    <div class="card-body">
      <div class="format-guide">
        <div class="format-card">
          <div class="format-name">🎵 TikTok</div>
          <div class="format-detail">
            Ratio: 9:16 vertical<br>
            Resolution: 1080×1920<br>
            Max length: 10 minutes<br>
            Sweet spot: 15–60 sec<br>
            File: MP4 recommended
          </div>
        </div>
        <div class="format-card">
          <div class="format-name">📸 Instagram Reels</div>
          <div class="format-detail">
            Ratio: 9:16 vertical<br>
            Resolution: 1080×1920<br>
            Max length: 90 seconds<br>
            Sweet spot: 15–30 sec<br>
            File: MP4 recommended
          </div>
        </div>
        <div class="format-card">
          <div class="format-name">▶️ YouTube Shorts</div>
          <div class="format-detail">
            Ratio: 9:16 vertical<br>
            Resolution: 1080×1920<br>
            Max length: 60 seconds<br>
            Sweet spot: 30–60 sec<br>
            File: MP4 recommended
          </div>
        </div>
        <div class="format-card">
          <div class="format-name">🟦 Instagram Feed</div>
          <div class="format-detail">
            Ratio: 1:1 or 4:5<br>
            Resolution: 1080×1080<br>
            Max length: 60 seconds<br>
            Sweet spot: 15–30 sec<br>
            File: MP4 recommended
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- CONNECT SOCIALS -->
  <div class="card">
    <div class="card-header">
      <div class="card-icon">🔗</div>
      <div class="card-title">Connect Your Accounts</div>
    </div>
    <div class="card-body">
      <p style="font-size:13px;color:var(--muted);margin-bottom:18px;">Connect your social accounts to schedule and publish clips directly without leaving ClipForge.</p>
      <div class="social-grid" id="social-grid">

        <div class="social-account-card" id="card-tiktok">
          <div class="social-platform-header">
            <div class="platform-logo tiktok">🎵</div>
            <div>
              <div class="platform-name">TikTok</div>
              <div class="platform-status" id="status-tiktok">Not connected</div>
            </div>
          </div>
          <div class="account-username" id="user-tiktok"></div>
          <button class="connect-btn" id="btn-tiktok" onclick="openConnect('tiktok')">Connect TikTok</button>
        </div>

        <div class="social-account-card" id="card-instagram">
          <div class="social-platform-header">
            <div class="platform-logo instagram">📸</div>
            <div>
              <div class="platform-name">Instagram</div>
              <div class="platform-status" id="status-instagram">Not connected</div>
            </div>
          </div>
          <div class="account-username" id="user-instagram"></div>
          <button class="connect-btn" id="btn-instagram" onclick="openConnect('instagram')">Connect Instagram</button>
        </div>

        <div class="social-account-card" id="card-youtube">
          <div class="social-platform-header">
            <div class="platform-logo youtube">▶️</div>
            <div>
              <div class="platform-name">YouTube Shorts</div>
              <div class="platform-status" id="status-youtube">Not connected</div>
            </div>
          </div>
          <div class="account-username" id="user-youtube"></div>
          <button class="connect-btn" id="btn-youtube" onclick="openConnect('youtube')">Connect YouTube</button>
        </div>

        <div class="social-account-card" id="card-twitter">
          <div class="social-platform-header">
            <div class="platform-logo twitter">𝕏</div>
            <div>
              <div class="platform-name">X (Twitter)</div>
              <div class="platform-status" id="status-twitter">Not connected</div>
            </div>
          </div>
          <div class="account-username" id="user-twitter"></div>
          <button class="connect-btn" id="btn-twitter" onclick="openConnect('twitter')">Connect X</button>
        </div>

        <div class="social-account-card" id="card-facebook">
          <div class="social-platform-header">
            <div class="platform-logo facebook">f</div>
            <div>
              <div class="platform-name">Facebook</div>
              <div class="platform-status" id="status-facebook">Not connected</div>
            </div>
          </div>
          <div class="account-username" id="user-facebook"></div>
          <button class="connect-btn" id="btn-facebook" onclick="openConnect('facebook')">Connect Facebook</button>
        </div>

      </div>
    </div>
  </div>

  <!-- SCHEDULER -->
  <div class="card scheduler-section" id="scheduler-card">
    <div class="card-header">
      <div class="card-icon">📅</div>
      <div class="card-title">Schedule Uploads</div>
    </div>
    <div class="card-body">

      <div class="connected-accounts-bar" id="connected-accounts-bar">
        <span class="no-accounts-msg" id="no-accounts-msg">Connect at least one account above to schedule uploads.</span>
      </div>

      <div id="schedule-clips-list" class="schedule-clips-list"></div>

      <div id="schedule-queue-wrap" style="display:none">
        <div class="schedule-queue">
          <div class="queue-header">
            Upload Queue <span class="queue-count" id="queue-count">0</span>
          </div>
          <div id="queue-list"></div>
        </div>
        <button class="schedule-all-btn" onclick="scheduleAll()">🚀 Schedule All Uploads</button>
      </div>

    </div>
  </div>

</div>

<!-- CONNECT MODAL -->
<div class="modal-backdrop" id="connect-modal">
  <div class="modal">
    <button class="modal-close" onclick="closeModal()">✕</button>
    <div class="modal-logo" id="modal-logo"></div>
    <h2 id="modal-title">Connect Account</h2>
    <p id="modal-desc">Enter your credentials to link this account to ClipForge.</p>

    <div class="modal-field">
      <label>Username / Handle</label>
      <input type="text" id="modal-username" placeholder="@yourhandle">
    </div>
    <div class="modal-field">
      <label>API Key / Access Token</label>
      <input type="password" id="modal-token" placeholder="Paste your access token">
    </div>

    <div class="oauth-note">
      🔒 In a real deployment this would use OAuth 2.0 so you never enter your password here. Your token is stored locally only.
    </div>

    <div class="modal-footer">
      <button class="btn-secondary" onclick="closeModal()">Cancel</button>
      <button class="btn-primary" onclick="confirmConnect()">Connect Account</button>
    </div>
  </div>
</div>

<div class="toast" id="toast">
  <span class="toast-icon" id="toast-icon">✅</span>
  <span id="toast-msg">Done!</span>
</div>

<script>
// ─── STATE ───────────────────────────────────────────────────────────────────
let videoFile = null;
let videoURL = null;
let videoDuration = 0;
let generatedClips = [];

// ─── UPLOAD ──────────────────────────────────────────────────────────────────
const fileInput = document.getElementById('file-input');
const uploadZone = document.getElementById('upload-zone');

uploadZone.addEventListener('dragover', e => { e.preventDefault(); uploadZone.classList.add('dragover'); });
uploadZone.addEventListener('dragleave', () => uploadZone.classList.remove('dragover'));
uploadZone.addEventListener('drop', e => {
  e.preventDefault();
  uploadZone.classList.remove('dragover');
  const f = e.dataTransfer.files[0];
  if (f && f.type.startsWith('video/')) loadVideo(f);
  else showToast('⚠️', 'Please drop a video file');
});

fileInput.addEventListener('change', () => {
  if (fileInput.files[0]) loadVideo(fileInput.files[0]);
});

function loadVideo(file) {
  videoFile = file;
  if (videoURL) URL.revokeObjectURL(videoURL);
  videoURL = URL.createObjectURL(file);

  const player = document.getElementById('video-player');
  player.src = videoURL;

  player.addEventListener('loadedmetadata', () => {
    videoDuration = player.duration;
    document.getElementById('video-preview-section').style.display = 'block';
    document.getElementById('settings-card').style.display = 'block';
    document.getElementById('timeline-section').style.display = 'block';

    const meta = document.getElementById('video-meta');
    meta.innerHTML = `
      <div class="meta-item">📄 ${file.name}</div>
      <div class="meta-item">⏱ ${formatTime(videoDuration)}</div>
      <div class="meta-item">💾 ${(file.size/1024/1024).toFixed(1)} MB</div>
      <div class="meta-item">🎬 ${file.type.replace('video/','').toUpperCase()}</div>
    `;

    updateTimeline();
    showToast('✅', 'Video loaded successfully!');
  }, { once: true });
}

// ─── SETTINGS ────────────────────────────────────────────────────────────────
function toggleOpt(el) {
  el.classList.toggle('on');
  if (el.id === 'toggle-watermark') {
    document.getElementById('watermark-input').style.display = el.classList.contains('on') ? 'block' : 'none';
  }
}

document.getElementById('clip-duration').addEventListener('change', updateTimeline);
document.getElementById('num-clips').addEventListener('change', updateTimeline);
document.getElementById('clip-mode').addEventListener('change', updateTimeline);

// ─── TIMELINE ────────────────────────────────────────────────────────────────
function updateTimeline() {
  if (!videoDuration) return;
  const clipDur = parseInt(document.getElementById('clip-duration').value);
  const numClipsVal = document.getElementById('num-clips').value;
  const maxPossible = Math.floor(videoDuration / clipDur);
  const numClips = numClipsVal === 'auto' ? maxPossible : Math.min(parseInt(numClipsVal), maxPossible);
  const mode = document.getElementById('clip-mode').value;

  const info = document.getElementById('clips-info');
  info.innerHTML = `
    <div class="clip-badge">📹 <span>${numClips}</span> clips</div>
    <div class="clip-badge">⏱ <span>${clipDur}s</span> each</div>
    <div class="clip-badge">📦 Total: <span>${formatTime(numClips * clipDur)}</span></div>
    <div class="clip-badge">Mode: <span>${mode}</span></div>
  `;

  // Draw timeline preview
  const bar = document.getElementById('timeline-bar');
  const track = document.getElementById('timeline-track');
  const pct = (clipDur / videoDuration) * 100;
  track.style.width = pct + '%';
  track.style.left = '0%';
  track.innerHTML = `<div class="timeline-label">Clip 1 (${clipDur}s preview)</div>`;
}

// ─── GENERATE CLIPS ──────────────────────────────────────────────────────────
async function generateClips() {
  if (!videoFile) return;

  const clipDur = parseInt(document.getElementById('clip-duration').value);
  const numClipsVal = document.getElementById('num-clips').value;
  const mode = document.getElementById('clip-mode').value;
  const addCaptions = document.getElementById('toggle-captions').classList.contains('on');
  const addWatermark = document.getElementById('toggle-watermark').classList.contains('on');
  const watermarkText = document.getElementById('watermark-text').value || '@mychannel';

  const maxPossible = Math.floor(videoDuration / clipDur);
  const numClips = numClipsVal === 'auto' ? maxPossible : Math.min(parseInt(numClipsVal), maxPossible);

  if (numClips === 0) {
    showToast('⚠️', `Video too short for ${clipDur}s clips`);
    return;
  }

  // Show progress
  document.getElementById('progress-section').style.display = 'block';
  document.getElementById('clips-section').style.display = 'none';
  document.getElementById('generate-btn').disabled = true;
  generatedClips = [];
  clearLog();

  // Calculate start times based on mode
  let startTimes = [];
  if (mode === 'spread') {
    const spacing = videoDuration / numClips;
    for (let i = 0; i < numClips; i++) startTimes.push(i * spacing);
  } else if (mode === 'random') {
    const usable = videoDuration - clipDur;
    const positions = [];
    for (let i = 0; i < numClips * 10 && positions.length < numClips; i++) {
      const t = Math.random() * usable;
      if (!positions.some(p => Math.abs(p - t) < clipDur)) positions.push(t);
    }
    positions.sort((a, b) => a - b);
    startTimes = positions.slice(0, numClips);
    if (startTimes.length < numClips) {
      for (let i = startTimes.length; i < numClips; i++) startTimes.push(i * (videoDuration / numClips));
    }
  } else if (mode === 'start') {
    for (let i = 0; i < numClips; i++) startTimes.push(i * clipDur);
  } else if (mode === 'end') {
    const base = videoDuration - (numClips * clipDur);
    for (let i = 0; i < numClips; i++) startTimes.push(Math.max(0, base) + i * clipDur);
  }

  addLog('info', `Processing ${numClips} clips from "${videoFile.name}"`);
  addLog('info', `Duration: ${clipDur}s each · Mode: ${mode}`);

  // Process each clip using canvas + MediaRecorder
  const video = document.createElement('video');
  video.src = videoURL;
  video.muted = true;
  video.preload = 'auto';
  await new Promise(r => { video.onloadeddata = r; });

  const canvas = document.createElement('canvas');
  // Set canvas to 9:16 vertical format (TikTok/Reels)
  const targetW = 540, targetH = 960;
  canvas.width = targetW;
  canvas.height = targetH;
  const ctx = canvas.getContext('2d');

  for (let i = 0; i < numClips; i++) {
    setProgress(((i) / numClips) * 90, `Processing clip ${i + 1} of ${numClips}...`);
    addLog('ok', `⚡ Clip ${i + 1}: starts at ${formatTime(startTimes[i])}`);

    try {
      const blob = await captureClip(video, canvas, ctx, startTimes[i], clipDur, addCaptions, addWatermark, watermarkText, i + 1);
      generatedClips.push({ blob, start: startTimes[i], duration: clipDur, index: i + 1 });
    } catch(e) {
      addLog('info', `⚠️ Clip ${i+1}: using snapshot mode`);
      const blob = await fallbackClip(video, canvas, ctx, startTimes[i], clipDur, addCaptions, addWatermark, watermarkText, i + 1);
      generatedClips.push({ blob, start: startTimes[i], duration: clipDur, index: i + 1 });
    }
  }

  setProgress(100, 'All clips ready!');
  addLog('ok', `✅ Done! ${numClips} clips generated`);

  await new Promise(r => setTimeout(r, 500));

  // Show results
  renderClips();
  document.getElementById('generate-btn').disabled = false;
  showToast('🎉', `${numClips} clips ready to download!`);
}

// ─── CLIP CAPTURE ────────────────────────────────────────────────────────────
function captureClip(video, canvas, ctx, startTime, duration, addCaptions, addWatermark, watermarkText, clipNum) {
  return new Promise((resolve, reject) => {
    const stream = canvas.captureStream(30);
    let recorder;
    try {
      recorder = new MediaRecorder(stream, { mimeType: 'video/webm;codecs=vp9', videoBitsPerSecond: 2500000 });
    } catch(e) {
      try {
        recorder = new MediaRecorder(stream, { mimeType: 'video/webm' });
      } catch(e2) {
        reject(e2); return;
      }
    }

    const chunks = [];
    recorder.ondataavailable = e => { if (e.data.size > 0) chunks.push(e.data); };
    recorder.onstop = () => {
      const blob = new Blob(chunks, { type: 'video/webm' });
      resolve(blob);
    };

    video.currentTime = startTime;
    video.onseeked = () => {
      recorder.start(100);
      video.play();

      const endTime = startTime + duration;
      let frame = 0;
      const W = canvas.width, H = canvas.height;

      const draw = () => {
        if (video.currentTime >= endTime || video.ended) {
          video.pause();
          recorder.stop();
          return;
        }

        // Draw video scaled to fill 9:16 canvas (letterbox/crop)
        const vw = video.videoWidth, vh = video.videoHeight;
        const vAspect = vw / vh;
        const cAspect = W / H;
        let sx, sy, sw, sh;
        if (vAspect > cAspect) {
          sh = vh; sw = vh * cAspect; sx = (vw - sw) / 2; sy = 0;
        } else {
          sw = vw; sh = vw / cAspect; sx = 0; sy = (vh - sh) / 2;
        }
        ctx.drawImage(video, sx, sy, sw, sh, 0, 0, W, H);

        // Dark gradient overlay at bottom
        const grad = ctx.createLinearGradient(0, H * 0.5, 0, H);
        grad.addColorStop(0, 'rgba(0,0,0,0)');
        grad.addColorStop(1, 'rgba(0,0,0,0.6)');
        ctx.fillStyle = grad;
        ctx.fillRect(0, 0, W, H);

        // Captions
        if (addCaptions) {
          const elapsed = video.currentTime - startTime;
          const captions = getCaptions(clipNum, duration);
          const current = captions.find(c => elapsed >= c.start && elapsed < c.end);
          if (current) {
            ctx.save();
            ctx.font = 'bold 42px "Arial Black", Impact, sans-serif';
            ctx.textAlign = 'center';
            ctx.lineWidth = 8;
            ctx.strokeStyle = 'rgba(0,0,0,0.9)';
            ctx.strokeText(current.text, W/2, H * 0.72);
            ctx.fillStyle = 'white';
            ctx.fillText(current.text, W/2, H * 0.72);
            ctx.restore();
          }
        }

        // Watermark
        if (addWatermark && watermarkText) {
          ctx.save();
          ctx.font = 'bold 22px Arial';
          ctx.fillStyle = 'rgba(255,255,255,0.85)';
          ctx.textAlign = 'right';
          ctx.fillText(watermarkText, W - 16, 36);
          ctx.restore();
        }

        // Clip number badge
        ctx.save();
        ctx.fillStyle = 'rgba(124,92,252,0.85)';
        ctx.beginPath();
        ctx.roundRect(14, 14, 70, 28, 6);
        ctx.fill();
        ctx.font = 'bold 14px Arial';
        ctx.fillStyle = 'white';
        ctx.textAlign = 'center';
        ctx.fillText(`CLIP ${clipNum}`, 49, 32);
        ctx.restore();

        frame++;
        requestAnimationFrame(draw);
      };

      requestAnimationFrame(draw);
    };
  });
}

// Fallback: create a single-frame image-based "clip" for unsupported browsers
async function fallbackClip(video, canvas, ctx, startTime, duration, addCaptions, addWatermark, watermarkText, clipNum) {
  return new Promise(resolve => {
    video.currentTime = startTime + duration * 0.5;
    video.onseeked = () => {
      const W = canvas.width, H = canvas.height;
      const vw = video.videoWidth, vh = video.videoHeight;
      const vAspect = vw / vh;
      const cAspect = W / H;
      let sx, sy, sw, sh;
      if (vAspect > cAspect) {
        sh = vh; sw = vh * cAspect; sx = (vw - sw) / 2; sy = 0;
      } else {
        sw = vw; sh = vw / cAspect; sx = 0; sy = (vh - sh) / 2;
      }
      ctx.drawImage(video, sx, sy, sw, sh, 0, 0, W, H);

      const grad = ctx.createLinearGradient(0, H * 0.5, 0, H);
      grad.addColorStop(0, 'rgba(0,0,0,0)');
      grad.addColorStop(1, 'rgba(0,0,0,0.65)');
      ctx.fillStyle = grad;
      ctx.fillRect(0, 0, W, H);

      if (addCaptions) {
        ctx.save();
        ctx.font = 'bold 42px "Arial Black", Impact, sans-serif';
        ctx.textAlign = 'center';
        ctx.lineWidth = 8;
        ctx.strokeStyle = 'rgba(0,0,0,0.9)';
        ctx.strokeText('Clip ' + clipNum, W/2, H * 0.72);
        ctx.fillStyle = 'white';
        ctx.fillText('Clip ' + clipNum, W/2, H * 0.72);
        ctx.restore();
      }

      if (addWatermark && watermarkText) {
        ctx.save();
        ctx.font = 'bold 22px Arial';
        ctx.fillStyle = 'rgba(255,255,255,0.85)';
        ctx.textAlign = 'right';
        ctx.fillText(watermarkText, W - 16, 36);
        ctx.restore();
      }

      ctx.save();
      ctx.fillStyle = 'rgba(124,92,252,0.85)';
      ctx.beginPath();
      ctx.roundRect(14, 14, 70, 28, 6);
      ctx.fill();
      ctx.font = 'bold 14px Arial';
      ctx.fillStyle = 'white';
      ctx.textAlign = 'center';
      ctx.fillText(`CLIP ${clipNum}`, 49, 32);
      ctx.restore();

      canvas.toBlob(blob => resolve(blob), 'image/jpeg', 0.9);
    };
  });
}

// Generate timed captions for clips
function getCaptions(clipNum, duration) {
  const sets = [
    ['Watch this 🔥', 'You won\'t believe it', 'Like & Follow!'],
    ['POV:', 'When you realize...', 'This is wild 😮'],
    ['Wait for it...', 'BOOM 💥', 'Drop a comment!'],
    ['Real talk 💯', 'Facts only', 'Share this!'],
    ['No cap 🧢', 'This hits different', 'Save this!'],
  ];
  const phrases = sets[(clipNum - 1) % sets.length];
  const seg = duration / phrases.length;
  return phrases.map((text, i) => ({ text, start: i * seg, end: (i + 1) * seg }));
}

// ─── RENDER CLIPS ────────────────────────────────────────────────────────────
function renderClips() {
  document.getElementById('clips-section').style.display = 'block';
  const grid = document.getElementById('clips-grid');
  grid.innerHTML = '';

  generatedClips.forEach(clip => {
    const url = URL.createObjectURL(clip.blob);
    const isVideo = clip.blob.type.startsWith('video/');
    const ext = isVideo ? 'webm' : 'jpg';
    const filename = `clip_${clip.index}_${Math.round(clip.start)}s.${ext}`;

    const card = document.createElement('div');
    card.className = 'clip-card';

    let mediaEl = '';
    if (isVideo) {
      mediaEl = `<video src="${url}" loop muted playsinline preload="metadata"></video>`;
    } else {
      mediaEl = `<img src="${url}" style="width:100%;height:100%;object-fit:cover;">`;
    }

    card.innerHTML = `
      <div class="clip-preview">
        ${mediaEl}
        <div class="clip-overlay">
          <div class="clip-number">CLIP ${clip.index}</div>
        </div>
      </div>
      <div class="clip-info">
        <div class="clip-name">Clip ${clip.index}</div>
        <div class="clip-duration">⏱ ${clip.duration}s · starts at ${formatTime(clip.start)}</div>
        <div class="clip-actions">
          <a href="${url}" download="${filename}" class="btn-download">⬇ Download</a>
          ${isVideo ? `<button class="btn-play" onclick="previewClip(this, '${url}')">▶ Play</button>` : ''}
        </div>
      </div>
    `;

    grid.appendChild(card);

    // Auto-play preview on hover
    if (isVideo) {
      const v = card.querySelector('video');
      card.addEventListener('mouseenter', () => v.play());
      card.addEventListener('mouseleave', () => { v.pause(); v.currentTime = 0; });
    }
  });
}

function previewClip(btn, url) {
  const card = btn.closest('.clip-card');
  const v = card.querySelector('video');
  if (v.paused) { v.play(); btn.textContent = '⏸ Pause'; }
  else { v.pause(); btn.textContent = '▶ Play'; }
}

// ─── UTILS ───────────────────────────────────────────────────────────────────
function formatTime(s) {
  const m = Math.floor(s / 60);
  const sec = Math.floor(s % 60);
  return `${m}:${sec.toString().padStart(2,'0')}`;
}

function setProgress(pct, text) {
  document.getElementById('progress-bar').style.width = pct + '%';
  document.getElementById('progress-text').textContent = text;
}

function addLog(type, msg) {
  const box = document.getElementById('log-box');
  const line = document.createElement('div');
  line.className = `log-line log-${type}`;
  line.textContent = msg;
  box.appendChild(line);
  box.scrollTop = box.scrollHeight;
}

function clearLog() {
  document.getElementById('log-box').innerHTML = '';
}

function showToast(icon, msg) {
  const t = document.getElementById('toast');
  document.getElementById('toast-icon').textContent = icon;
  document.getElementById('toast-msg').textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 3500);
}

// Init
updateTimeline();

// ─── SOCIAL ACCOUNTS ─────────────────────────────────────────────────────────
const connectedAccounts = {};
let currentPlatform = null;

const platformMeta = {
  tiktok:    { label: 'TikTok',          emoji: '🎵', bg: '#010101', color: '#69C9D0' },
  instagram: { label: 'Instagram',       emoji: '📸', bg: 'linear-gradient(135deg,#f09433,#dc2743,#bc1888)', color: '#fc5c9c' },
  youtube:   { label: 'YouTube Shorts',  emoji: '▶️', bg: '#FF0000', color: '#FF4444' },
  twitter:   { label: 'X (Twitter)',     emoji: '𝕏',  bg: '#000',    color: '#aaa' },
  facebook:  { label: 'Facebook',        emoji: 'f',  bg: '#1877F2', color: '#5b9bd5' },
};

function openConnect(platform) {
  const meta = platformMeta[platform];
  currentPlatform = platform;

  const logo = document.getElementById('modal-logo');
  logo.textContent = meta.emoji;
  logo.style.background = meta.bg;

  document.getElementById('modal-title').textContent = `Connect ${meta.label}`;
  document.getElementById('modal-desc').textContent =
    `Link your ${meta.label} account to publish and schedule clips directly from ClipForge.`;
  document.getElementById('modal-username').value = '';
  document.getElementById('modal-token').value = '';
  document.getElementById('connect-modal').classList.add('open');
  setTimeout(() => document.getElementById('modal-username').focus(), 100);
}

function closeModal() {
  document.getElementById('connect-modal').classList.remove('open');
  currentPlatform = null;
}

// Close modal on backdrop click
document.getElementById('connect-modal').addEventListener('click', function(e) {
  if (e.target === this) closeModal();
});

function confirmConnect() {
  const username = document.getElementById('modal-username').value.trim();
  const token = document.getElementById('modal-token').value.trim();

  if (!username) { showToast('⚠️', 'Please enter a username'); return; }
  if (!token)    { showToast('⚠️', 'Please enter your access token'); return; }

  const platform = currentPlatform;
  const meta = platformMeta[platform];

  connectedAccounts[platform] = { username, token };

  // Update card UI
  const card = document.getElementById(`card-${platform}`);
  card.classList.add('connected');

  const statusEl = document.getElementById(`status-${platform}`);
  statusEl.textContent = 'Connected ✓';
  statusEl.classList.add('ok');

  const userEl = document.getElementById(`user-${platform}`);
  userEl.textContent = username.startsWith('@') ? username : '@' + username;
  userEl.style.display = 'block';

  const btn = document.getElementById(`btn-${platform}`);
  btn.textContent = 'Disconnect';
  btn.classList.add('connected');
  btn.onclick = () => disconnectAccount(platform);

  closeModal();
  showToast('✅', `${meta.label} connected as ${username}`);
  refreshConnectedBar();
  refreshScheduler();
}

function disconnectAccount(platform) {
  delete connectedAccounts[platform];
  const meta = platformMeta[platform];

  const card = document.getElementById(`card-${platform}`);
  card.classList.remove('connected');

  document.getElementById(`status-${platform}`).textContent = 'Not connected';
  document.getElementById(`status-${platform}`).classList.remove('ok');
  document.getElementById(`user-${platform}`).style.display = 'none';

  const btn = document.getElementById(`btn-${platform}`);
  btn.textContent = `Connect ${meta.label}`;
  btn.classList.remove('connected');
  btn.onclick = () => openConnect(platform);

  showToast('ℹ️', `${meta.label} disconnected`);
  refreshConnectedBar();
  refreshScheduler();
}

function refreshConnectedBar() {
  const bar = document.getElementById('connected-accounts-bar');
  const noMsg = document.getElementById('no-accounts-msg');
  const keys = Object.keys(connectedAccounts);

  if (keys.length === 0) {
    bar.innerHTML = '<span class="no-accounts-msg" id="no-accounts-msg">Connect at least one account above to schedule uploads.</span>';
    return;
  }

  bar.innerHTML = '<span style="font-size:12px;color:var(--muted);font-weight:600;margin-right:4px;">Posting to:</span>';
  keys.forEach(p => {
    const meta = platformMeta[p];
    const acc = connectedAccounts[p];
    const badge = document.createElement('div');
    badge.className = 'connected-badge';
    badge.innerHTML = `${meta.emoji} ${acc.username}`;
    bar.appendChild(badge);
  });
}

// ─── SCHEDULER ───────────────────────────────────────────────────────────────
const scheduleQueue = [];

function refreshScheduler() {
  const hasClips = generatedClips.length > 0;
  const hasAccounts = Object.keys(connectedAccounts).length > 0;

  const schedulerCard = document.getElementById('scheduler-card');
  schedulerCard.style.display = 'block';

  const list = document.getElementById('schedule-clips-list');
  list.innerHTML = '';

  if (!hasClips) {
    list.innerHTML = '<p style="font-size:13px;color:var(--muted);padding:8px 0;">Generate clips first — they will appear here to schedule.</p>';
    return;
  }

  generatedClips.forEach((clip, i) => {
    const row = document.createElement('div');
    row.className = 'schedule-clip-row';
    row.style.gridTemplateColumns = '1fr';
    row.style.gap = '10px';

    // Default scheduled time: spread clips 6 hours apart starting from next hour
    const base = new Date();
    base.setMinutes(0, 0, 0);
    base.setHours(base.getHours() + 1 + i * 6);
    const defaultDT = base.toISOString().slice(0, 16);

    const connectedPlatformChips = Object.keys(connectedAccounts).map(p => {
      const meta = platformMeta[p];
      return `<span class="platform-chip selected" data-platform="${p}" onclick="toggleChip(this)">${meta.emoji} ${meta.label}</span>`;
    }).join('');

    row.innerHTML = `
      <div style="display:flex;align-items:center;gap:10px">
        <div class="schedule-clip-thumb">🎬</div>
        <div class="schedule-clip-info" style="flex:1">
          <div class="schedule-clip-name">Clip ${clip.index}</div>
          <div class="schedule-clip-time">⏱ ${clip.duration}s · starts at ${formatTime(clip.start)}</div>
        </div>
      </div>
      <div>
        <div class="section-label" style="margin-bottom:6px">Platforms</div>
        <div class="schedule-platforms" id="chips-${i}">
          ${connectedPlatformChips || '<span style="font-size:12px;color:var(--muted)">No accounts connected</span>'}
        </div>
      </div>
      <div>
        <div class="section-label" style="margin-bottom:6px">Scheduled time</div>
        <input type="datetime-local" class="schedule-datetime" id="dt-${i}" value="${defaultDT}">
      </div>
      <div>
        <div class="section-label" style="margin-bottom:6px">Caption & hashtags</div>
        <textarea class="caption-input" id="caption-${i}" maxlength="2200"
          placeholder="Write a caption... #viral #fyp #trending"
          oninput="updateCharCount(this, 'cc-${i}')">#viral #fyp #trending #shorts</textarea>
        <div class="char-count" id="cc-${i}">27 / 2200</div>
      </div>
      <button class="connect-btn" style="width:auto;align-self:flex-start;padding:8px 18px"
        onclick="addToQueue(${i})">+ Add to Queue</button>
    `;

    list.appendChild(row);
  });
}

function toggleChip(chip) {
  chip.classList.toggle('selected');
}

function updateCharCount(textarea, countId) {
  const el = document.getElementById(countId);
  if (el) el.textContent = `${textarea.value.length} / 2200`;
}

function addToQueue(clipIndex) {
  const clip = generatedClips[clipIndex];
  const dt = document.getElementById(`dt-${clipIndex}`).value;
  const caption = document.getElementById(`caption-${clipIndex}`).value;
  const chips = document.querySelectorAll(`#chips-${clipIndex} .platform-chip.selected`);
  const platforms = Array.from(chips).map(c => c.dataset.platform);

  if (!dt) { showToast('⚠️', 'Please set a scheduled time'); return; }
  if (platforms.length === 0) { showToast('⚠️', 'Select at least one platform'); return; }

  const entry = {
    id: Date.now() + clipIndex,
    clipIndex,
    clip,
    dt,
    caption,
    platforms,
    status: 'queued',
  };

  scheduleQueue.push(entry);
  renderQueue();
  showToast('📅', `Clip ${clip.index} added to queue`);
}

function renderQueue() {
  const wrap = document.getElementById('schedule-queue-wrap');
  const qList = document.getElementById('queue-list');
  const qCount = document.getElementById('queue-count');

  if (scheduleQueue.length === 0) {
    wrap.style.display = 'none';
    return;
  }

  wrap.style.display = 'block';
  qCount.textContent = scheduleQueue.length;
  qList.innerHTML = '';

  scheduleQueue.forEach((entry, idx) => {
    const dtLabel = new Date(entry.dt).toLocaleString(undefined, {
      month: 'short', day: 'numeric', hour: '2-digit', minute: '2-digit'
    });
    const platformLabels = entry.platforms.map(p => platformMeta[p].emoji + ' ' + platformMeta[p].label).join(', ');
    const statusClass = entry.status === 'scheduled' ? 'scheduled' : entry.status === 'posted' ? 'posted' : '';

    const item = document.createElement('div');
    item.className = 'queue-item';
    item.id = `queue-item-${entry.id}`;
    item.innerHTML = `
      <div class="queue-status ${statusClass}"></div>
      <div class="queue-item-info">
        <div class="queue-item-name">Clip ${entry.clip.index}</div>
        <div class="queue-item-meta">${platformLabels} · ${dtLabel}</div>
        ${entry.caption ? `<div class="queue-item-meta" style="margin-top:2px;font-style:italic">"${entry.caption.slice(0,50)}${entry.caption.length>50?'…':''}"</div>` : ''}
      </div>
      <button class="queue-item-remove" onclick="removeFromQueue(${idx})" title="Remove">✕</button>
    `;
    qList.appendChild(item);
  });
}

function removeFromQueue(idx) {
  scheduleQueue.splice(idx, 1);
  renderQueue();
}

function scheduleAll() {
  if (scheduleQueue.length === 0) return;

  scheduleQueue.forEach((entry, idx) => {
    const delay = new Date(entry.dt) - new Date();
    entry.status = 'scheduled';

    const queueItem = document.getElementById(`queue-item-${entry.id}`);
    if (queueItem) {
      const dot = queueItem.querySelector('.queue-status');
      if (dot) dot.className = 'queue-status scheduled';
    }

    // Simulate posting at scheduled time (in a real app this calls the platform APIs)
    const timeoutMs = delay > 0 ? delay : 1000 + idx * 800;
    setTimeout(() => simulatePost(entry), timeoutMs);
  });

  const earliest = scheduleQueue.map(e => new Date(e.dt)).sort((a,b) => a-b)[0];
  const label = earliest.toLocaleString(undefined, { month:'short', day:'numeric', hour:'2-digit', minute:'2-digit' });
  showToast('🚀', `${scheduleQueue.length} clips scheduled! First post: ${label}`);
  renderQueue();
}

function simulatePost(entry) {
  entry.status = 'posted';
  const queueItem = document.getElementById(`queue-item-${entry.id}`);
  if (queueItem) {
    const dot = queueItem.querySelector('.queue-status');
    if (dot) dot.className = 'queue-status posted';
    const meta = queueItem.querySelector('.queue-item-meta');
    if (meta) {
      const posted = document.createElement('div');
      posted.className = 'queue-item-meta';
      posted.style.color = 'var(--success)';
      posted.style.fontWeight = '600';
      posted.textContent = '✓ Posted successfully';
      queueItem.querySelector('.queue-item-info').appendChild(posted);
    }
  }
  showToast('✅', `Clip ${entry.clip.index} posted to ${entry.platforms.map(p => platformMeta[p].label).join(', ')}!`);
}

// Re-render scheduler whenever clips are generated
const _origRenderClips = renderClips;
renderClips = function() {
  _origRenderClips();
  refreshScheduler();
};
</script>
</body>
</html>
