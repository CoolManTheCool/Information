# Help for Flashing USB (or similar) devices

## Balena Etcher

### Issue: Stuck on White Window

#### Diagnostics:
- Users may encounter the error message: `Authorization required, but no authorization protocol specified`.
- The Balena Etcher window appears white, with functional buttons but no interface.

#### Solutions:
- Run the following command in the terminal to resolve the authorization issue:
  ```bash
  xhost si:localuser:root
  ```

#### Sources:
- [Reddit thread discussing the "Authorization required" error](https://www.reddit.com/r/linux4noobs/comments/lu1plx/hi_i_get_this_authorization_required_but_no/) (Accessed: 9:01 AM CDT 5/11/24)
