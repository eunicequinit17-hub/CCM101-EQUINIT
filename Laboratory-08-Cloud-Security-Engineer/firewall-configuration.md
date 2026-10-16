

# Firewall Configuration

## 1. Allow SSH

```bash
sudo ufw allow ssh
```

This rule allows SSH connections for remote server administration.

## 2. Set the Default Policies

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```

These commands block incoming connections by default and allow outgoing connections.

## 3. Enable the Firewall

```bash
sudo ufw enable
sudo ufw status verbose
```

These commands activate the firewall and display its status and default policies.

## 4. Allow the Web Application Port

```bash
sudo ufw allow 8080/tcp
sudo ufw status numbered
```

This rule permits incoming TCP traffic on port 8080 for the web application.

## 5. Importance of Allowing SSH First

If I enable UFW before allowing SSH, incoming SSH connections may be blocked and I could lose remote access to the server.
